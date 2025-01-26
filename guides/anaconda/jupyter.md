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
