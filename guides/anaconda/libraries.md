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
| Cursos                    | 1. [NumPy](#NumPy) | 2. [OpenCV](#OpenCV) | 2. [Matplotlib](#Matplotlib) | 3. scikit-learn | 7. sympy |
| :------------------------ | :---:              | :---:                | :---:                        | :---:           | :---:    |
| Visión por computadora    | ✓                  | ✓                   | ✓                            | ✓              |           |
| Señales y sistemas        | ✓                  |                     | ✓                            |                 | ✓        |
</div>
    
> **Nota:** Sigue el orden para evitar errores durante la instalación.

<br/>
  
## NumPy

- En la consola escribe el siguiente comando:

  ```console
  conda install main::numpy
  ```

- Confirma la instalación escribiendo [y] cuando se solicite.
- Note que `NumPy` se instala automáticamente junto con muchos paquetes científicos.

**Verificar la instalación (opcional)**

Una vez instalada la libreria, puedes verificar si fue instalada correctamente:
- Escribe el siguiente comando en la terminal:

  ```console
  python -c "import numpy as np; print(np.__version__)"
  ```
  
- Si no aparece ningún error ¡NumPy fue instalado correctamente! y deberias observar algo como:

  ```console
  (cv) PS C:\Users\jferb> python -c "import numpy as np; print(np.__version__)"
  2.4.1
  (cv) PS C:\Users\jferb>
  ```

[librerias](#tb-libs)

<br/>

## OpenCV

- En la consola escribe el siguiente comando:

  ```console
  conda install main::opencv
  ```

- Confirma la instalación escribiendo [y] cuando se solicite.

**Verificar la instalación (opcional)**

Una vez instalada la libreria, puedes verificar si esta fue instalada correctamente:

- Escribe el siguiente comando en la terminal:

  ```console
  python -c "import cv2; print(cv2.__version__)"
  ```
  
- Si no aparece ningún error e imprime la versión entonces ¡OpenCV fue instalado correctamente!

[librerias](#tb-libs)

<br/>

## Matplotlib

- Escribe el siguiente comando en la terminal para instalar Matplotlib usando conda:

  ```console
  conda install main::matplotlib
  ```

- Cuando aparezca un mensaje de confirmación, escribe [y] y presiona `Enter` para continuar.

**Verificar la instalación (opcional)**

Una vez la instalación ha terminado, verifica si Matplotlib se instaló correctamente:

- Escribe el siguiente comando en la terminal:

  ```console
  python -c "import matplotlib as plt; print(plt.__version__)"
  ```
  
- Si no aparece ningún error y muestra una versión (por ejemplo, 3.x.x), Matplotlib fue instalado correctamente.

<br/>

## Scikit-learn

- Escribe el siguiente comando en la terminal para instalar scikit-learn usando conda:

  ```console
    conda install main::scikit-learn
  ```

- Cuando aparezca un mensaje de confirmación, escribe [y] y presiona `Enter` para continuar.

**Verificar la instalación (opcional)**

Una vez la instalación ha terminado, verifica si scikit-learn se instaló correctamente:

- Escribe el siguiente comando en la terminal:

  ```console
     python -c "import sklearn; sklearn.show_versions()"
  ```
  
- Si no aparece ningún error y muestra la versión y otros datos de sus dependencias (blas u openmp) la libreria fue correctamente instalado.

<br/>

[librerias](#tb-libs)

[Página principal](../../README.md)
