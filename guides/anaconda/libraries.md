<div  align="center">
    
# Librerias para Python

Sigue los pasos para instalar las diversas librerias de Python requeridas.

</div>

> [!CAUTION]
> Antes de instalar cualquier libreria o paquete recuerda **activar** el entorno virtual.

# Lista de librerias
1. [NumPy](#NumPy)
2. [Example2](#example2)

**Activación del entorno**

- Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).

- Una vez has creado el entorno virtual, activa el nuevo entorno:

    ```console
   conda activate nombre_entorno
   ```

- Sustituye `nombre_entorno` con el nombre del entorno virtual que desea utilizar. por ejemplo `ai` para SEA (Semillero en Electrónica Aplicada).
  
## NumPy

- En la consola escribe el siguiente comando:

  ```console
  conda install numpy
  ```

- Confirma la instalación escribiendo [y] cuando se solicite.

- Note que `NumPy` se instala automáticamente con muchos paquetes científicos en Anaconda, como Jupyter Notebook y SciPy.

**Verificar la instalación**

Una vez instalada, puedes verificar si NumPy se instaló correctamente:

- Escribe `python` en la terminal para abrir el intérprete de Python. Luego escribe:

  ```console
  import numpy as np
  print(np.__version__)
  ```
  
- Si no aparece ningún error y muestra una versión, ¡NumPy está instalado correctamente!

## Instalar Matplotlib

- Escribe el siguiente comando en la terminal para instalar Matplotlib usando conda:

  ```console
  conda install matplotlib
  ```

- Cuando aparezca un mensaje de confirmación, escribe [y] y presiona `Enter` para continuar.

**Verificar la instalación**

Una vez que la instalación haya terminado, verifica si Matplotlib se instaló correctamente:

- Escribe `python` en la terminal para abrir el intérprete de Python. Luego, escribe este código para probar:

  ```console
  import matplotlib.pyplot as plt
  print(plt.__version__)
  ```
  
- Si no aparece ningún error y muestra una versión (por ejemplo, 3.x.x), Matplotlib está instalado correctamente.

<br/>

[Página principal](../../README.md)
