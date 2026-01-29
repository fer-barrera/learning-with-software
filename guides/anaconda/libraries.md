<div  align="center">
    
# Librerias para Python

Sigue los pasos para instalar las diversas librerias de Python requeridas.

</div>

<br/>
<br/>

> [!CAUTION]
> Antes de instalar cualquier libreria o paquete recuerda **activar** el entorno virtual.

<br/>

| :zap: | **Activación del entorno** |
|-------|:---------------------------|

- Ejecuta `Anaconda Powershell Prompt` (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt).
- Activa el entorno:

    ```console
   conda activate nombre_entorno
   ```

- Sustituye `nombre_entorno` con el nombre del entorno virtual que desea utilizar. por ejemplo `cv` para curso de visión por computadora.

<br/>

<a name="tb-libs"></a>

## 📚 Instalación de librerias

  1. **Localiza tu curso:** Revisa la Tabla 1, columna **"Cursos"**.  
  2. **Instala las librerias marcadas con "✓":** Ignorando aquellas sin símbolo.
  3. **Sigue el orden de las columnas:** De izquierda a derecha, conforme al número asignado a cada columna.

<div  align="center">
    
**Tabla 1.** Librerias
| Cursos                    | 1. [NumPy](#NumPy) | 2. [OpenCV](#OpenCV) | 2. [Matplotlib](#Matplotlib) | 3. opencv-contrib | 4. scikit-learn | 5. pandas | 6. seaborn |
| :------------------------ | :---:              | :---:                | :---:                        | :---:             | :---:           | :---:     | :---:     |
| Visión por computadora    | ✓                  | ✓                   | ✓                            |                   |                 |           |           |

</div>
    
> **Nota:** Sigue el orden para evitar errores durante la instalación.

<br/>
  
## NumPy

- En la consola escribe el siguiente comando:

  ```console
  conda install conda-forge::numpy
  ```

- Confirma la instalación escribiendo [y] cuando se solicite.
- Note que `NumPy` se instala automáticamente junto con muchos paquetes científicos.

**Verificar la instalación (opcional)**

Una vez instalada la libreria, puedes verificar si fue instalada correctamente:
- Escribe `python` en la terminal para abrir el intérprete de Python. Luego escribe:

  ```console
  import numpy as np
  print(np.__version__)
  exit()
  ```
  
- Si no aparece ningún error ¡NumPy fue instalado correctamente! y deberias observar algo como:

  ```console
  (base) PS C:\Users\jferb> python
  Python 3.11.5 | packaged by Anaconda, Inc. | (main, Sep 11 2023, 13:26:23) [MSC v.1916 64 bit (AMD64)] on win32
  Type "help", "copyright", "credits" or "license" for more information.
  >>> import numpy as np
  >>> print(np.__version__)
  1.26.4
  >>> exit()
  (base) PS C:\Users\jferb>
  ```

[librerias](#tb-libs)

<br/>

## OpenCV

- En la consola escribe el siguiente comando:

  ```console
  conda install conda-forge::opencv
  ```
<!--- pip install opencv-contrib-python --->

- Confirma la instalación escribiendo [y] cuando se solicite.

**Verificar la instalación (opcional)**

Una vez instalada la libreria, puedes verificar si fue instalada correctamente:
- Escribe `python` en la terminal para abrir el intérprete de Python. Luego escribe:

  ```console
  import cv2
  print(cv2.__version__)
  exit()
  ```
  
- Si no aparece ningún error e implime la versión entonces ¡OpenCV fue instalado correctamente!

[librerias](#tb-libs)

<br/>

## Matplotlib

- Escribe el siguiente comando en la terminal para instalar Matplotlib usando conda:

  ```console
  conda install conda-forge::matplotlib
  ```

- Cuando aparezca un mensaje de confirmación, escribe [y] y presiona `Enter` para continuar.

**Verificar la instalación (opcional)**

Una vez la instalación ha terminado, verifica si Matplotlib se instaló correctamente:

- Escribe `python` en la terminal para abrir el intérprete de Python. Luego, escribe el código de prueba:

  ```console
  import matplotlib.pyplot as plt
  print(plt.__version__)
  exit()
  ```
  
- Si no aparece ningún error y muestra una versión (por ejemplo, 3.x.x), Matplotlib fue instalado correctamente.

<br/>

[librerias](#tb-libs)

[Página principal](../../README.md)
