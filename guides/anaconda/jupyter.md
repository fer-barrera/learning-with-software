# Jupyter y configuración de un entorno virtual como Kernel

Sigue estos pasos para instalar Jupyter Notebook y configurar tu entorno virtual para que funcione como un kernel en Jupyter.

**Activación del entorno**

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

- Usa el siguiente comando para registrar tu entorno virtual en Jupyter Notebook. Sustituye nombre_entorno con el nombre que desees mostrar en Jupyter:

    ```console
    ipython kernel install --user --name=nombre_entorno-kernel
    ```

- Por ejemplo,  sustituye nombre_entorno-kernel por `ai-kernel` para SEA (Semillero en Electrónica Aplicada).
