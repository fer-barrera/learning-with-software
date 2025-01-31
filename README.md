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
En el ámbito de la Ingeniería Electrónica, la integración de herramientas software se ha convertido en un factor determinante para el desarrollo de proyectos académicos e investigativos de alto impacto. Con el propósito de apoyar estas actividades, se ha desarrollado Learning with Software, un repositorio que reúne un conjunto de guías de instalar, configurar, y poner en marcha de diversos recursos software, principalmente Python, para el exito  en areas como: ciencias de la computación, visión por computadora, matemáticas, e ingeniría.



Este repositorio reúne un conjunto de guías para instalar varias herramientas software que apoyan procesos educativos e investigativos en el programa de Ingenieria Electrónia de la Universidad Surcolombiana. Cada guía presenta en forma resumida el procedimiento para instalar, configurar, y poner en marcha algún desarrollo software, principalmente en Python. Ente otros objetivos este repositorio pretende fomentar y agilizar el aprendizaje e investigación a traves del software, en areas como: ciencias de la computación, visión por computadora, matemáticas, e ingeniría.

## Configuración del entorno de desarrollo

La siguiente tabla presenta el listado de aplicaciones y librerías necesarias para configurar tu entorno de desarrollo según tu curso.

### Instrucciones

1. **Identifica tu curso:** Busca el nombre de tu curso en la columna **"Cursos"**.
2. **Identifica las acciones requeridas:** Revisa las columnas siguientes ya que ellas indican que aplicación, librería o instrucción deberas ejecutar para tener tu entorno de desarrollo operativo. Solo son necesarias aquellas que tienen el simbolo **"✓"**. Una celda vacia indica omitir o no realizar.
3. **Sigue el orden:** Instala cada elemento en el orden en el que aparecen las columnas, es decir, de izquierda a derecha.

### Tabla de configuración

| Cursos                    | 1. Anaconda | 2. Entorno virtual[^1] | 3. Jupyter | 4. numpy | 5. matplotlib | 6. scikit-learn | 7. pandas |
| :------------------------ | :---------: | :---                   | :---:      | :---:    | :---:         | :---:           | :---:           |
| Visión por computadora    | ✓           | cv                     | ✓         | ✓        | ✓             | ✓              | :---:           |
| Señales y sistemas        | ✓           | signalsys              | ✓         | ✓        | ✓             |                 |:---:           |
| Calculo diferencial       | ✓           | math                   | ✓         | ✓        | ✓             |                 |:---:           |
| SEA                       | ✓           | ai                     | ✓         | ✓        | ✓             |  ✓              |:---:           |
| Servicios web             | ✓           | websrv                 |           |           | ✓             |                 |:---:           |

[^1]: Nombre sugerido para el entorno virtual (no es obligatorio).

> **Nota:** Sigue el orden indicado de izquierda a derecha para evitar errores durante la instalación.

### Guías de instalación

- [Anaconda](guides/anaconda/anaconda-install.md)
- [Entorno virtual](guides/anaconda/virtual-environments.md)
- [Jupyter](guides/anaconda/jupyter.md)
- [Librerias](guides/anaconda/libraries.md)
