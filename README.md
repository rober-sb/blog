# Blog

_Pequeño proyecto de un blog, _

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Necesitaras instalar un paquete para convertir tu computadora en un servidor local como LARAGON, XAMPP, LAMPP o alguno de tu agrado. _

```
Yo tengo instalado LARAGON por su facilidad de uso.
```

### Instalación 🔧

```
_1. Bien, lo primero que debemos hacer es ejecutar el paquete que encendera nuestro servidor local._

```
```
_2. Luego, debemos colocar los archivos dentro de una carpeta que crearemos dentro del "root" del programa que estemos utilizando._

```
```
_3. Abrimos la terminal, colocamos "npm run dev" y ejecutamos_

```
```
_4. Crearemos una base de datos que se llame "campus"._

```
```
_5. En la terminal nuevamente colocaremos "php artisan migrate --seed" y ejecutamos para enviar todos los datos necesarios y de prueba a la BD_

```
```
_6. En este momento podriamos ir a la pagina de nuestro servidor local._

```
```
_7. Si por alguna razón, no visualiza los datos puede colocar en la terminal "php artisna serve" y ejecutar._

```
En mi caso que utilicé LARAGON.

```
1. Creó una carpeta llamado proyecto_blog dentro de root y luego coloco dentro de proyecto_blog los archivos del repositorio.

```
```
2. Despues de esto, enciendo el servidor local.

```
```
3. Creo una base de datos llamada "campus" y en la terminal ejecuto el comando "php artisan migrate --seed".

```
```
4. Luego ejecuto el comando "npm artisan serve"

```
```
5. Al final podremos observar la pagina local y sino logramos visulizarla aún podemos ejecutar el comando "php artisan serve".
```
## Construido con 🛠️

* [Laragon](http://www.dropwizard.io/1.0.2/docs/) - Paquete para servidor local
* [Laravel](http://www.dropwizard.io/1.0.2/docs/) - El framework utilizado
* [Composer](https://maven.apache.org/) - Manejador de dependencias
* [booststrap](https://rometools.github.io/rome/) - Usado para generar lo visual
