## NODE JS
Es JavaScript para el lado del servidor, es decir ejecutar código JavaScript en el servidor, fuera del navegador. EL motor UV8 de google por ejemplo nos permite ejecutar JavaScript en el servidor para trabajar con este programa como BackEnd.

*Ejm: node app.js*

## NPM
NPM (Node Package Manager) Gestiona dependecias (Bibliotecas y Módulos) de nuestros proyectos Node.js, NPM facilita la instalación de paquetes desde un repositorio en línea y la gestión de versiones (16, 18, 20, etc.), ayudando a mantener proyectos organizados y actualizados. 

## NVM

Es un gestor de versiones que permite gestionar múltiples versiones de Node.js en un mismo sistema. Podemos instalar diferentes versiones de Node.js y cambiar entre ellas según sea necesario. Esto es útil para probar y ejecutar proyectos que requieren diferentes versiones de Node.js.

Se puede descargar desde: https://github.com/coreybutler/nvm-windows/releases

Recomendado: **nvm-setup.exe**

Comandos: 

- **nvm install** : Instala una versión específica de Node.js. Si solo usas nvm install node, instalará la última versión disponible.
- **nvm uninstall** : Desinstala una versión específica.
- **nvm list** : Muestra todas las versiones de Node.js que tienes instaladas en tu sistema. Aparece un **(*)** en la que se encuentra activa.
- **nvm use** : Cambia a una versión específica de Node.js
- **nvm --version** ó -v: Muestra la versión de NVM que tienes instalada en tu sistema.
- **node --version** ó -v: Muestra la versión actual de Node.js  
    *TIP : Siempre verificar con node -v la versión en el terminal que nos toque trabajar* 

## YARN

Yarn es un gestor de paquetes para JavaScript, similar a NPM, que se utiliza para instalar, compartir y gestionar dependencias de proyectos. Fue desarrollado por Facebook para mejorar la velocidad, seguridad y consistencia en la gestión de dependencias.


## DEPENDENCIAS

Las dependencias son bibliotecas o módulos de código que un proyecto necesita para funcionar correctamente. En JavaScript herramientas como NPM o YARN nos permiten trabajar de esta manera,en resumen son paquetes externos que se incluyen en nuestro proyecto para añadir funcionalidades específicas sin tener que escribir todo el código desde cero.

Las dependencias se especifican en un archivo de configuración, como **package.json** en proyectos de Node.js, y se gestionan mediante comandos que las instalan, actualizan o eliminan según sea necesario.

**Tipos de Instalacióm**
- Global : Instalación en todo el Sistema Operativo.
- DEV: Instalación en mi ambiente de desarrollo (En mi proyecto).
- PROD: Instalación en producción.

Se crea la carpeta **node_modules** la cual nunca se sube a un repositorio y es la contiene las dependencia a usar pero la carpeta fundamental es package.json porque con ella incluso se puede regenerar la carpeta node_nodules

## VITE JS

Vite es una herramienta de desarrollo rápida y moderna para proyectos web grandes y escalables que usa el concepto **"Bundle"** (Empaquetado tipo started) instalación de dependencias. 

Para instalar puedes usar **NPM** y **YARN** para instalar VITE JS.

No instala dependencias se debe especificar NPM o YARN según instalación.

Scripts a considerar en el package.json de VITE JS:

- **dev:** Levanta ambiente de desarrollo para trabajar.
- **build:** Empaquetado (serie de archivos) subirlo a la nube html, css, javascript e imágenes.
- **preview:** Levanta el proyecto para ver en producción.