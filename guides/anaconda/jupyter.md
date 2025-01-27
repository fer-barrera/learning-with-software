# Jupyter y configuración de un entorno virtual como Kernel

Sigue estos pasos para instalar Jupyter Notebook y configurar tu entorno virtual para que funcione como un kernel en Jupyter.

**Activación del entorno**

- Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).

- Una vez has creado el entorno virtual, activa el nuevo entorno:

    ```console
   conda activate nombre_entorno
   ```

- Sustituye `nombre_entorno` con el nombre del entorno virtual que desea utilizar. por ejemplo `ai` para SEA (Semillero en Electrónica Aplicada).
  
**Instala el paquete ipykernel**

- Agrega el soporte de kernel para el entorno virtual activado, en la consola digita el siguiente comando:

  ```console
  conda install -c anaconda ipykernel
  ```
  
**Registrar el entorno virtual como un kernel**

- Usa el siguiente comando para registrar tu entorno virtual en Jupyter Notebook. Sustituye 'nombre_entorno' con el nombre que desees mostrar en Jupyter:

    ```console
    ipython kernel install --user --name=nombre_entorno-kernel
    ```

- En el anterior comando sustituye nombre_entorno-kernel por `ai-kernel` para el Semillero en Electrónica Aplicada (SEA). Si fue ejecutado correctamente, deberas observar una salida similar a:

    ```console
    (ai) PS C:\Users\jferb> ipython kernel install --user --name=ai-kernel
    Installed kernelspec ai-kernel in C:\Users\jferb\AppData\Roaming\jupyter\kernels\ai-kernel
    (ai) PS C:\Users\jferb>
    ```

**Inicia Jupyter Notebook**

- Para ejecutar Jupyter tiene dos opciones:
    
    - Ejecutar desde el menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Jupiter Notebook.
    
    - Ó Ejecuta el siguiente comando desde la consola:

       ```console
       jupyter notebook
       ```

    - Recuerde que Jupyter estará activo **mientras la consola permanezca abierta**. Si cierra la cierra, el servidor de Jupyter se detendrá, lo que hará que la página web de Jupyter Notebook deje de funcionar.
