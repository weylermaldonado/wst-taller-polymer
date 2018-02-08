# Polymer
## Creación nativa de un custom element

Necesitaremos:
* npm
* bower
* polyserve
* webcomponentsjs

En la carpeta del proyecto, iniciar un proyecto con bower

```bash
$ bower init
```
Posteriormente, instala **_webcomponentsjs_**
```bash
$ bower install --save webcomponentsjs 
```
Luego instalemos polyserve
```bash
 sudo npm isntall polyserve -g
```
Creemos un archivo llamado `index.html`, dentro de las etiquetas `<head>`, importemos el siguiente archivo
```html
<script src="/bower_components/webcomponentsjs/webcomponents-loader.js"></script>
```
## Instalación (producción)

Para usar Polymer en producción necesitas:
* bower
* webcomponentsjs
* polymer
* Nodejs
Seguidamente, instalar la libería **_Polymer_**

```bash
$ npm install -g polymer-cli
```

La bandera _--save_ es para agregar la dependencia al archivo bower.json

Iniciemos un nuevo proyecto con Polymer
```bash
$ polymer init
```

## Instalación (CDN)

Importar la siguiente etiqueta en el archivo que va a consumir el webcomponent

```html
<script src="https://polygit.org/components/webcomponentsjs/webcomponents-lite.js"></script>
```

Importar la siguiente etiqueta en el archivo que será consumido como webcomponent

```html
<link rel="import" href="https://polygit.org/components/polymer/polymer.html">
```

