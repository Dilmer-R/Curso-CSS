# Cómo agregar CSS

Cuando un navegador lee una hoja de estilo, formateará el documento HTML de acurdo a la info de la hoja de estilo.

Ahora te presento, tres formas de insertar CSS.

- CSS externo:

Esta es la forma más recomendable de agregar estilos a nuestra página web, se dice que es externa porque vamos a crear un archivo externo y luego lo agregamos o importamos a nuestro documento HTML.

<h3>Ejemplo:</h3>

- Documento index.html
```html
<!-- Documento HTML -->
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="css/style.css" rel="stylesheet"> 
        <!--Estamos traendo el archivo css externo, que está dentro de la carpeta css en este caso-->
    </head>
    <body>
        <h1>Hola mundo</h1>
    </body>
</html>
```
- Documento css/style.css
```css
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
```
- CSS interno:

Esto no es muy recomendable, se refiere a que agregamos dentro de nuenstro documento HTML la tag(etiqueta) ```<style>``` en el ```<head>``` y dentro de esta, añadimos todos los estilos que queremos.

<h3>Ejemplo:</h3>

- Documento index.html
```html
<!-- Documento HTML -->
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
            body {
                background-color: linen;
            }
            h1 {
                color: maroon;
                margin-left: 40px;
            }
        </style>
    </head>
    <body>
        <h1>Hola mundo</h1>
    </body>
</html>
```

- CSS en línea:

Se puede aplicar un estilo en línea a un elemento de html, se selecciona el elemento y dentro se le añade el atributo ```style="color:blue;"``` con su propiedad y su valor.

<h3>Ejemplo:</h3>

- Documento index.html
```html
<!-- Documento HTML -->
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        
    </head>
    <body>
        <h1 style="color:blue;">Hola mundo</h1>
    </body>
</html>
```

# Orden o jerarquía de como agregar CSS

La pregunta es: 

- ¿Qué estilo se utilizará cuando haya más de un estilo especificado para un elemento HTML?

Todos los estilos en una página, "Caeran en cascada", bien ahora estas son las prioridades.

1. Estilo en línea.
2. Hojas de estilos extarnas e internas.
3. Predeterminado del navegador.

En conclusión, los estilos en línea son la prioridad más alta.

Por tanto, por esto no es recomendable agregar estilos en línea.


- NOTA: Desarrollar la homework.
