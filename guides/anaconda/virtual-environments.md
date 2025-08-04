<div  align="center">

# Creación de un entorno virtual con Conda

Un entorno virtual de Python es un espacio aislado que permite instalar paquetes y dependencias específicas para un proyecto, sin afectar la configuración global del sistema. Facilita la gestión de versiones y evita conflictos entre proyectos. Existen diversas herramientas para crear entornos virtuales en Python, como por ejemplo: `virtualenv`, `venv` y `conda`. De estas opciones, la ultima es la más sencilla y práctica. A continuación, se presenta una serie de pasos para crear un entorno virtual utilizando la interfaz `conda`.

</div>

<br/>

## 📝 Guía para crear un entorno virtual

1. Verifica que ecosistema `conda` esta instalado correctamente:
   - Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).
   - Digita conda -V en la consola.
  
       ```console
       conda -V
       ```
   - Si `conda` está instalado correctamente en su sistema, usted deberá observar una salida similar a:
     
      ```console
      (base) PS C:\Users\jferb> conda -V
      conda 23.7.4
      ```
   
2. Nombre del entorno virtual
   - Selecciona un nombre adecuado para tu entorno virtual. Asegúrate de evitar espacios en blanco, caracteres especiales, acentos u otros símbolos. 
   - Se recomienda utilizar un nombre simple y descriptivo.

<div  align="center">
  
**Tabla 1.** Lista de aplicaciones
| Aplicaciones                                                                    | Visión por computadora |
| :------------------------------------------------------------------------------ | :--------------------: |
| 1. [Anaconda](guides/anaconda/anaconda-install.md)                              | ✓                      |
| 2. [Configuración del Entorno virtual](guides/anaconda/virtual-environments.md) | ✓                      |
| 3. [Jupyter](guides/anaconda/jupyter.md)                                        | ✓                      |
| 4. [Librerias](guides/anaconda/libraries.md)                                    | ✓                      |

</div>
  
   - Para listar todos los entornos virtuales existentes en tu sistema y evitar nombres duplicados, ejecute el siguiente comando en la consola:
  
      ```console
      conda env list
      ```

3. Creación del nuevo entorno virtual (🌎)
   - Una vez has instalado `conda` y seleccionado el nombre de tu entorno virtual, puedes crearlo, para ello utiliza el comando `conda create`, como se muestra a continuación:

      ```console
      conda create --name nombre_entorno python=3.8
      ```

      | :point_up:    | Recuerda modificar: *nombre_entorno* por el sugerido! |
      |---------------|:------------------------|

   - Por ejemplo, para crear un entorno virtual para el Semillero en Electrónica Aplicada con Python `3.8.0` sustituye `nombre_entorno` con `ai`. Recuerda que puedes cambiar su nombre y la versión de Python preinstalada. 

4. Activación del entorno
   - Una vez has creado el entorno virtual, **activa** el nuevo entorno:

      ```console
      conda activate nombre_entorno
      ```
      
   - Si el comando se ejecutó correctamente, deberías observar algo similar a:

     ```console
     (base) PS C:\Users\jferb> conda activate ai
     (ia) PS C:\Users\jferb>
     ```
<br/>

> [!TIP]
> Recuerda **activar** el entorno antes de instalar una nueva libreria o paquete.

<br/>

[Página principal](../../README.md)
