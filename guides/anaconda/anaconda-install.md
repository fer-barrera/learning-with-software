<div  align="center">
   
# Anaconda

[Anaconda](https://www.anaconda.com/) es **un ecosistema multiplataforma** para el desarrollo de aplicaciones en Python. Este incluye tanto **herramientas** como **librerias precompiladas**, especialmente diseñadas para facilitar la gestión de recursos computacionales en proyectos de aprendizaje automático, ciencia de datos, sistemas distribuidos, e inteligencia artificial, solo por mencionar algunos.

</div>

<br/><br/>

> [!CAUTION]
> Antes de realizar alguna acción, primero lea las instrucciones asociadas.

<br/>

## 📝 Guía de instalación

1. Descargue el instalador de [Anaconda](https://www.anaconda.com/download).
   - Tenga en cuenta que no es necesario proporcionar su correo electrónico, ni suscribirse al servicio de Anaconda Cloud. Seleccione la opción [skip registration](https://www.anaconda.com/download/success).
     
2. Ejecute el instalador y preste **atención** a las siguientes opciones:
   - **Installation for (⚙️):** seleccione la opción ''**All users**''. Esto permite instalar el entorno en la raíz del disco. En particular, fuera de la carpeta: mis documentos, lo cual es muy importante para la gestión de los entornos virtuales. Esta acción requiere la clave de administrador (🗝️).
   - **Choose install location (📁):** Cuando se pregunte por la ruta de instalación escriba: `C:\apps\anaconda3`
   - **Advanced installation options (📌):** Cuando se pregunte por las opciones avanzadas de instalación, seleccione la opción: ''**Register Anaconda3 as the system Python 3.x**'' (✔️). Esto habilita el entorno virtual base de Anaconda como el interprete por defecto del sistema operativo.
    
3. Finalice el proceso de instalación.
   
4. Verifique su instalación:
   - En el menu de inicio de windows debera observar una carpeta con el nombre Anaconda3 (64/32-bits), y en su interior aplicaciones como: Anaconda Navigator, Anaconda Prompt, Anaconda Powershell Prompt, entre otras.
   - Ejecute Anaconda Powershell Prompt (menu inicio windows &rarr;  Anaconda3 (64-bit) &rarr; Anaconda Powershell Prompt) y luego escriba:
     
      ```console
      python --version
      ```
   
   - El anterior comando debera imprimir la versión del interprete python. Por ejemplo:
     
      ```console
      (base) PS C:\Users\jferb> python --version
      Python 3.11.5
      ```
<br/>

## Fix “Command Not Found” (Windows)

Si la instalación de Anaconda termina correctamente pero al ejecutar `conda` en la terminal aparece que el comando no existe, agregue manualmente las carpetas de Anaconda a la variable de entorno **PATH**.

Rutas típicas a agregar:

- `...\Anaconda3`
- `...\Anaconda3\Scripts`

<br/>

<details>
  <summary><strong>📌 Ver pasos para editar el PATH en Windows</strong></summary>

  1. **Abra la configuración de variables de entorno**
     - Presione la tecla **Windows** y escriba: **Editar las variables de entorno del sistema** ( o edit the system environment variables)
     - Abra el resultado.

  2. **Entre a Variables de entorno**
     - En la ventana **Propiedades del sistema**, pestaña **Opciones avanzadas**, haga clic en **Variables de entorno…**

  3. **Edite la variable PATH**
     - En **Variables del sistema** (recomendado), busque **Path** y seleccione **Editar…**  
       *(También puede hacerlo en “Variables de usuario” si quiere aplicarlo solo a su cuenta).*

  4. **Agregue las rutas de Anaconda**
     - Haga clic en **Nuevo** y agregue una por una (según su instalación):
       - `C:\apps\Anaconda3`
       - `C:\apps\Anaconda3\Scripts`

  5. **Guarde los cambios**
     - Presione **Aceptar** en todas las ventanas para confirmar.

  6. **Reabra la terminal y verifique**
     - Cierre y vuelva a abrir **CMD** o **PowerShell**.
     - Ejecute: `conda --version`

  **Nota:** Si Anaconda está instalada en otra ubicación, use esa ruta real; lo importante es incluir la carpeta principal y `Scripts`.

</details>

[Página principal](../../README.md)
