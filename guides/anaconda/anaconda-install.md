# Anaconda

[Anaconda](https://www.anaconda.com/) es **un ecosistema multiplataforma** para el desarrollo de aplicaciones en Python. Este incluye tanto **herramientas** como **librerias precompiladas**, especialmente diseñadas para facilitar la gestión de recursos computacionales en proyectos de aprendizaje automático, ciencia de datos, sistemas distribuidos, e inteligencia artificial, solo por mencionar algunos.

## Guía de instalación

1. Descargue el instalador de [Anaconda](https://www.anaconda.com/download).
   - Tenga en cuenta que no es necesario proporcionar su correo electrónico, ni suscribirse al servicio de Anaconda Cloud. Seleccione la opción [skip registration](https://www.anaconda.com/download/success).
     
2. ⚠️ Ejecute el instalador y preste **atención** a las siguientes opciones:
   - ⚙️ **Installation type:** seleccione la opción ''**All users**''. Esto permite instalar el entorno en la raíz del disco. En particular, fuera de la carpeta: mis documentos, lo cual es muy importante para la gestión de los entornos virtuales. Esta acción requiere la clave de administrador (🗝️).
   - 📁 **Choose install location:** Cuando se pregunte por la ruta de instalación escriba: `C:\apps\anaconda3`.
   - 📌 **Advanced installation options:** Cuando se pregunte por las opciones avanzadas de instalación, seleccione la opción: ''**Anaconda as my default Python 3.x environment**''. Esto habilita el entorno virtual base de Anaconda como el interprete por defecto del sistema operativo.
     
3. Finalice el proceso de instalación.
   
4. Verifique su instalación:
   - En el menu de inicio de windows debera observar una carpeta con el nombre Anaconda3 (64/32-bits), y en su interior aplicaciones como: Anaconda Navigator, Anaconda Prompt, Anaconda Powershell Prompt, entre otras.
   - Ejecute Anaconda Powershell Prompt y luego escriba:
     
      ```console
      python --version
      ```
   
   - El anterior comando debera imprimir la versión del interprete python. Por ejemplo:
     
      ```console
      (base) PS C:\Users\jferb> python --version
      Python 3.11.5
      ```
   
   
