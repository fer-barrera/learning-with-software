# Librerias para Python

Sigue estos pasos para instalar las librerias de Python.

**Activación del entorno**

- Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).

- Una vez has creado el entorno virtual, activa el nuevo entorno:

    ```console
   conda activate nombre_entorno
   ```

- Sustituye `nombre_entorno` con el nombre del entorno virtual que desea utilizar. por ejemplo `ai` para SEA (Semillero en Electrónica Aplicada).
  
**Instala el paquete NumPy**

- En la consola escribe el siguiente comando:

  ```console
  conda install numpy
  ```

- Confirma la instalación escribiendo [y] cuando se solicite.

- Note que `NumPy` se instala automáticamente con muchos paquetes científicos en Anaconda, como Jupyter Notebook y SciPy.

**Verificar la instalación**

Una vez instalada, puedes verificar si NumPy se instaló correctamente:

- Escribe `python` en la terminal para abrir el intérprete de Python.

  ```console
  import numpy as np
  print(np.__version__)
  ```
  
- Si no aparece ningún error y muestra una versión, ¡NumPy está instalado correctamente!


