# Run
Para visualizar el blog se corre el siguiente comando en la terminal

```
$ hugo server
```
Se corren ambos lenguages Es/En. 

Puerto 1314 es para idioma espanol y puerto 1313 es para idioma en ingles

### Editar Archivos
Los archivos con el contenido original del **TEMA** vienen en la carpeta themes. Para editar o personalizar algun template es necesario crear una copia de dicho archivo y su respectivo directorio en la raiz del proyecto.

Ejemplo:

Modificar el archivo custom.css del tema:

* Crear una carpeta `static` en la raiz del proyecto
* Agregar `css` y a continuacion copiar el archivo `custom.css`.
* Pasarlo a la carpeta creada.
* Una vez ahi, ya puede ser modificado 

### Lenguajes

Para crear los diferentes lenguajes, se debe configurar el archivo config.toml. En este documento se dan de alta los diferentes Lenguages que se van a usar:
```
[Languages.en]
baseurl = "https://example.en"
title = "Our blog"
weight = 1
```
Espanol es el lenguaje por defecto. 

### Posts
Para agregar post en espanol unicamente se agrega la entrada en la carpeta `blog`. Todas las entradas por defecto se veran en la pagina de espanol. Si se desea agregar entradas a ingles es necesario agregar la extension .en.md


### Hugo Documentation
[Hugo Documentation](https://gohugo.io/)

### Hugo Theme Documentation
[Hugo Universal Theme Documentation](https://themes.gohugo.io/hugo-universal-theme/)