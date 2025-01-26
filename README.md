# Learning with software
This repository provides detailed installation guides for essential software and tools designed to facilitate learning and research in computer science, mathematics, signals and systems, and computer vision. 

## Configuración del entorno de desarrollo

La siguiente tabla presenta el listado de aplicaciones y librerías necesarias para configurar tu entorno de desarrollo según tu curso.

### Instrucciones

1. **Identifica tu curso:** Busca el nombre de tu curso en la columna **"Cursos"**.
2. **Identifica las acciones requeridas:** Revisa las columnas siguientes ya que ellas indican que aplicación, librería o instrucción deberas ejecutar para tener tu entorno de desarrollo operativo. Solo son necesarias aquellas que tienen el simbolo **"✓"**. Una celda vacia indica omitir o no realizar.
3. **Sigue el orden:** Instala cada elemento en el orden en el que aparecen las columnas, es decir, de izquierda a derecha.

### Tabla de configuración

| Cursos                    | 1. Anaconda | Entorno virtual[^1] | 2. Jupiter |
| :------------------------ | :---------: | :---                | :---:      |
| Visión por computadora    | ✓           | cv                  | ✓         |
| Señales y sistemas        | ✓           | signalsys           | ✓         |
| Calculo diferencial       | ✓           | math                | ✓         |
| SEA                       | ✓           | ia                  | ✓         |
| Servicios web             | ✓           | websrv              |           |

[^1]: Nombre sugerido para el entorno virtual (no es obligatorio).

> **Nota:** Sigue el orden indicado de izquierda a derecha para evitar errores durante la instalación.

## Guías de instalación de software

- [Anaconda](guides/anaconda/anaconda-install.md)


Run the JDK tools from this Snap package in a stricty-confined environment:

```console
$ openjdk.javac --version
javac 22
$ openjdk.java --version
openjdk 22 2024-03-19
OpenJDK Runtime Environment (build 22+36-snap)
OpenJDK 64-Bit Server VM (build 22+36-snap, mixed mode, sharing)
```
