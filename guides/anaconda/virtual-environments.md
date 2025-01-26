# Creación de un entorno virtual con Conda

Existen diversas herramientas para crear entornos virtuales para Python, como por ejemplo: `virtualenv`, `venv` y `conda`. De estas opciones, la ultima es la más sencilla y práctica. A continuación, se presenta una lista de pasos para crear un entorno virtual utilizando la interfaz de `conda`:

## Pasos para Crear un Entorno Virtual

** Nombre del entorno virtual**
Seleccione un nombre para su entorno virtual, evite espacios en blanco, caracteres especiales, acentos y etc. Se suguiere utilizar el nombre por ejemplo: `ai` para el SEA (Semillero en Electrónica Aplicada).

3. **Abrir la Terminal o el Anaconda Prompt**  
   Asegúrate de tener instalado Anaconda o Miniconda en tu sistema.

4. **Verificar Entornos Existentes (Opcional)**  
   Lista todos los entornos disponibles para evitar nombres duplicados:  
   ```bash
   conda env list
