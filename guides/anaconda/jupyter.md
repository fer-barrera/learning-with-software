<div  align="center">

# Jupyter y configuración de un entorno virtual como Kernel
[Jupyter](https://jupyter.org/) es una aplicación web que permite crear y compartir documentos interactivos con código en vivo, visualizaciones y texto explicativo. Es ampliamente utilizado en ciencia de datos, aprendizaje automático y análisis numérico. Sigue los pasos para configurar tu entorno virtual como un kernel de Jupyter.

</div>

<br/><br/>

## 📝 Guía de configuración

1. Activación del entorno
    - Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).
    - Una vez has creado el entorno virtual, activa el nuevo entorno:
        ```console
       conda activate nombre_entorno
       ```
    - Sustituye `nombre_entorno` con el nombre del entorno virtual que desea utilizar. por ejemplo `ai` para el SEA (Semillero en Electrónica Aplicada).
  
2. Instala el paquete **ipykernel**
    - Agrega el soporte de kernel para el entorno virtual activado, en la consola digita el siguiente comando:

      ```console
      conda install -c anaconda ipykernel
      ```
  
3. Registrar el entorno virtual como un kernel
    - Usa el siguiente comando para registrar tu entorno virtual en Jupyter Notebook. Sustituye `nombre_entorno` con el nombre que desees mostrar en Jupyter:

        ```console
        ipython kernel install --user --name=nombre_entorno-kernel
        ```

    - En el anterior comando sustituye nombre_entorno-kernel por `ai-kernel` para el Semillero en Electrónica Aplicada (SEA). Si fue ejecutado correctamente, deberas observar una salida similar a:

        ```console
        (ai) PS C:\Users\jferb> ipython kernel install --user --name=ai-kernel
        Installed kernelspec ai-kernel in C:\Users\jferb\AppData\Roaming\jupyter\kernels\ai-kernel
        (ai) PS C:\Users\jferb>
        ```

4. Inicia Jupyter Notebook

    - Para ejecutar el servidor de Jupyter tiene dos opciones:
        - Ejecutar la aplicación desde el menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; :notebook: Jupiter Notebook.
        - Ó ejecutando el siguiente comando desde la consola:

           ```console
           jupyter notebook
           ```

    - Recuerde que Jupyter estará activo **mientras la consola permanezca abierta**. Si la cierra, o detiene el proceso, el servidor de Jupyter se detendrá, y el entorno de desarrollo web de Jupyter Notebook dejará de funcionar (página web).

<br/>

[Página principal](../../README.md)
