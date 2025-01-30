<h1 align="center">Learning with Software</h1>
<!---
## Tabla de contenido
- [About](#-about)
- [Certification](#-certification)
- [How to Build](#-how-to-build)
- [Documentation](#-documentation)
- [Feedback and Contributions](#-feedback-and-contributions)
- [License](#-license)
- [Contacts](#%EF%B8%8F-contacts)
--->

Este repositorio reúne un conjunto de guías de instalación para diversas aplicaciones y herramientas software. Estas presentan en forma resumida los pasos necesarios para la configuración y puesta en marcha de una plataforma de desarrollo software, principalmente basada en Python, para fomentar el aprendizaje e investigación en areas como: ciencias de la computación, visión por computadora, matemáticas, e ingeniría.

## Configuración del entorno de desarrollo

La siguiente tabla presenta el listado de aplicaciones y librerías necesarias para configurar tu entorno de desarrollo según tu curso.

### Instrucciones

1. **Identifica tu curso:** Busca el nombre de tu curso en la columna **"Cursos"**.
2. **Identifica las acciones requeridas:** Revisa las columnas siguientes ya que ellas indican que aplicación, librería o instrucción deberas ejecutar para tener tu entorno de desarrollo operativo. Solo son necesarias aquellas que tienen el simbolo **"✓"**. Una celda vacia indica omitir o no realizar.
3. **Sigue el orden:** Instala cada elemento en el orden en el que aparecen las columnas, es decir, de izquierda a derecha.

### Tabla de configuración

| Cursos                    | 1. Anaconda | 2. Entorno virtual[^1] | 3. Jupyter | 4. numpy | 5. matplotlib | 6. scikit-learn |
| :------------------------ | :---------: | :---                   | :---:      | :---:    | :---:         | :---:           |
| Visión por computadora    | ✓           | cv                     | ✓         | ✓        | ✓             | ✓              |
| Señales y sistemas        | ✓           | signalsys              | ✓         | ✓        | ✓             |                 |
| Calculo diferencial       | ✓           | math                   | ✓         | ✓        | ✓             |                 |
| SEA                       | ✓           | ai                     | ✓         | ✓        | ✓             |  ✓              |
| Servicios web             | ✓           | websrv                 |           |           | ✓             |                 |

[^1]: Nombre sugerido para el entorno virtual (no es obligatorio).

> **Nota:** Sigue el orden indicado de izquierda a derecha para evitar errores durante la instalación.

### Guías de instalación

- [Anaconda](guides/anaconda/anaconda-install.md)
- [Entorno virtual](guides/anaconda/virtual-environments.md)
- [Jupyter](guides/anaconda/jupyter.md)
- [Librerias](guides/anaconda/libraries.md)
