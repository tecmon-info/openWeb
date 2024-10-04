# openWeb

`openWeb` es un script que abre automáticamente tres pestañas en Google Chrome al iniciar tu equipo. Las pestañas incluyen la página de **Aules de FP**, la página de **login de OneDrive**, y una pestaña en blanco. Este script está pensado para facilitar el acceso a estas herramientas esenciales desde el momento en que enciendes tu ordenador.

## Descripción

Este script está diseñado para ejecutarse automáticamente cada vez que se inicia el sistema. Se coloca en la carpeta de inicio automático de Windows, lo que garantiza que al encender tu equipo se abrirán tres pestañas específicas en Google Chrome:

1. **Aules de FP**: Acceso directo a la plataforma educativa.
2. **OneDrive (login)**: Para iniciar sesión rápidamente en tu cuenta de OneDrive.
3. **Pestaña en blanco**: Una pestaña vacía para uso personal.

### Características:

- **Apertura automática**: Ejecuta Google Chrome con las pestañas seleccionadas al encender el equipo.
- **Fácil configuración**: No requiere configuración adicional, solo mover el script a la carpeta de inicio automático.
- **Compatible con Windows**: Funciona en sistemas Windows que tienen Google Chrome instalado.

## Requisitos

- **Google Chrome** debe estar instalado en el sistema.
- El script solo está diseñado para **Windows**.

## Instalación

### Paso 1: Descargar el script

1. Clona o descarga el script a tu ordenador:

```bash
git clone https://github.com/tu-repositorio/AutoChromeTabs.git
```

### Paso 2: Mover el script a la carpeta de inicio automático

Para que el script se ejecute automáticamente al encender el equipo, debes moverlo a la carpeta de Inicio automático de Windows:

1. Copiar el archivo `.cmd` descargado.
2. Pegar el archivo en la siguiente ruta:

```bash
C:\Users\%USERNAME%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
```

## Paso 3: Reiniciar el equipo

Una vez colocado el archivo en la carpeta de inicio automático, reinicia tu equipo para que el script se ejecute al iniciar el sistema.

## Uso

Cada vez que enciendas tu ordenador, Google Chrome se abrirá automáticamente con las siguientes pestañas:

1. **Aules FP**: [https://aules.edu.gva.es]
2. **Login de OneDrive**: [https://login.microsoftonline.com]
3. **Pestaña en blanco**

Estas pestañas se abrirán en el navegador predeterminado (Chrome) sin necesidad de interacción adicional por parte del usuario.

## Personalización

Si deseas cambiar las URLs que se abren o agregar más pestañas, puedes editar el script `.cmd`. Abre el archivo con un editor de texto y modifica las líneas de URLs según tus necesidades.

## Plataformas soportadas

- **Windows**: Este script está diseñado exclusivamente para sistemas operativos Windows.

## Advertencias

- Asegúrate de que Google Chrome esté instalado y configurado como tu navegador predeterminado. El script no funcionará correctamente con otros navegadores.
- Si deseas deshabilitar la ejecución automática, simplemente elimina el script de la carpeta de inicio automático.

## Licencia y Contribuciones

Este proyecto no tiene una licencia específica, pero está abierto a contribuciones. Si deseas mejorar o personalizar el código, puedes enviar un pull request para revisión.