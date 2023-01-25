# [Manual SASS](https://desarrolloweb.com/manuales/manual-sass.html)
[Tomado de la página web **desarrolloweb.com/manuales**](https://desarrolloweb.com/manuales/manual-sass.html)

# Compilar archivos SASS a CSS
Debemos tener un **archivo origen en sass** y un **archivo destino en css**, luego 
ejecutar el siguiente comando colocando el archivo origen y en seguida el de destino.
```
sass ./scss/01.inicio.scss ./css/01.inicio.css
```
Tras ejecutar el comando anterior, el código del archivo scss se compilará en el archivo destino con código css.

# Vigilar las modificaciones de un archivo en concreto
Para evitar estar ejecutando el comando anterior, podemos usar una bandera **--watch** para que
esté pendiente de los cambios y haga la compilación automática
```
sass --watch ./scss/01.inicio.scss ./css/01.inicio.css
```
# Vigilar todos los archivos de una carpeta
```
sass --watch carpetaorigen:carpetadestino
```
