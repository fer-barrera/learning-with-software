# Creación de un entorno virtual con Conda

Existen diversas herramientas para crear entornos virtuales en Python, como por ejemplo: `virtualenv`, `venv` y `conda`. De estas opciones, la ultima es la más sencilla y práctica. A continuación, se presenta una serie de pasos para crear un entorno virtual utilizando la interfaz `conda`.

## Pasos para crear un entorno virtual

**Verifica si conda esta instalado correctamente**
- Ejecuta `Anaconda Powershell Prompt` (menu de inicio de windows).
- Digita conda -V en la consola.
  
   ```console
   conda -V
   ```
   
- Si `conda` está instalado correctamente en su sistema, usted debera observar una salida similar a:
  
   ```console
  (base) PS C:\Users\jferb> conda -V
  conda 23.7.4
   ```
   
**Nombre del entorno virtual**

- Selecciona un nombre para tu entorno virtual. Asegúrate de evitar espacios en blanco, caracteres especiales, acentos u otros símbolos. 
- Se recomienda utilizar un nombre simple y descriptivo. Por ejemplo, para el **SEA** (Semillero en Electrónica Aplicada), se sugiere:  `ai`.
- Para listar todos los entornos virtuales existentes en tu sistema y evitar nombres duplicados, ejecute el siguiente comando en la consola:
  
   ```console
   conda env list
   ```

**Creación del nuevo entorno virtual**

- Una vez has instalado `conda` y seleccionado el nombre de tu entorno virtual, puedes crearlo, para ello utiliza el comando `conda create`, como se muestra a continuación:

    ```console
   conda create --name nombre_entorno python=3.8
   ```

- Por ejemplo, para crear un entorno virtual para el Semillero en Electrónica Aplicada con Python `3.8.0` sustituye `nombre_entorno` con `ai`. Recuerda que puedes cambiar su nombre y la versión de Python preinstalada. 

**Activación del entorno**

- Una vez has creado el entorno virtual, activa el nuevo entorno:

    ```console
   conda activate nombre_entorno
   ```
    
- Si el comando se ejecutó correctamente, deberías observar algo similar a:

  ```console
  (base) PS C:\Users\jferb> conda activate ia
  (ia) PS C:\Users\jferb>
  ```
  
- Recuerda **activar** el entorno simpre que instale una nueva libreria.
