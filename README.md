# Practica2-RDS


## Recursos

###Visual Code Editor
  [descargar] (https://code.visualstudio.com/)

  - ####Extensiones 
  
    1. Sublime Text Keymap
    2. vscode-icons
    3. Image preview
    4. HTML CSS Class Completion

  - ####Configuración
   
      Parametros de identacion, alineacion, tabs, y demas configuraciones basicas para visual code, se debe copiar y pegar en el editor
 => [ver](https://gist.github.com/daguiheso/3324b6df821ecb4f73b5166a6fb816c0)
 
***

###Normalize.css 
  
  Para hacer un reset del **CSS** en todos los navegadores y así hacer que se refleje lo mismo en todos los navegadores => [ver] (https://necolas.github.io/normalize.css/)

***

###HTML Special Characters

  Caracteres especiales de HTML [ver] (http://www.quackit.com/html/html_special_characters.cfm)
  
***

###SASS - GULPJS - BROWSER-SYNC

* SASS => Preprocesador CSS
* GULPJS => Automatiza tareas (compila, minifica, concatena archivos y mucho más)
* BROWSER-SYNC => Crea un servidor local y refresca navegador automaticamente en todos los dispositivos.

###Pasos para implementar

1. Abrir CMD/consola como administrador, ejecutar elsiguiente comando, esperar a que termine sin errores y cerrar consola
    
    `$ npm i gulp -g` 
   
2. Ir a visual code, abrir terminal en **menu** > **ver** > **terminal integrado** ,ejecutar comando y esperar a que termine:

    `$ npm init --yes`
    
   Este comando creara automaticamente un archivo llamado **package.json** en la raiz de nuestro proyecto, es un archivo de tipo informativo, donde se ven datos basicos de nuestro proyecto (nombre, autor, licencia) ademas de las dependencias (librerias requeridas) de de este.
    
3. En la misma terminal de visual code ejecutar el comando:

    `$ npm i gulp gulp-sass browser-sync --save`
    
    
   Con este comando estamos instalando las 3 librerias al tiempo, cuando se termine este proceso en consola, notamos que en nuestro archivo **package.json** se han agregado estas librerias y ademas se ha creado una carpeta node_modules en la raiz del proyecto.


4. Agregar archivo [gulpfile.js](https://raw.githubusercontent.com/daguiheso/Practica1-RDS/master/gulpfile.js) y [.gitignore] (https://raw.githubusercontent.com/daguiheso/Practica2-RDS/master/.gitignore) en la raiz del proyecto.
