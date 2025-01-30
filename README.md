<h1 align="center">Learning with software</h1>

This repository provides detailed installation guides for essential software and tools designed to facilitate learning and research in computer science, mathematics, signals and systems, and computer vision. 

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
