# Fondos CSS

Ahora vamos entrar mas a fondo en la propiedad background color.

Propiedades que vamos a aprender:
```html
1. background-color:
2. background-image:
3. background-repeat:
4. background-position:
5. background-attachment:
6. background-size: sirve para agregar medidas a la imagen.

```

<h3> 1. background-color: </h3>

* Como vimos en el artículo anterior, esta propiedad sirve para agregar un color de fondo a nuestra caja contenedora.

* Tambien además de esta propiedad, podemos agregarle otra que es opacity, con esta especificamos la opacidad o transparencia de el color de la caja contenedora.

Ejemplo: 

```css
h1 {
    background-color: #00ffff;
    opacity: 0.3;
}
```
- Acceder a la ```demo-01``` para ver un ejemplo sobre lo que comenté anteriromente.

<h3> 2. background-image: </h3>

* Esta propiedad establece una imagen de fondo a nuestra caja contenedora.

* Tenemos que especificar el link o ruta de imagen a agregar.

Ejemplo 1: Por ruta interna 

```css
h1 {
    background-image: url(../imagen/imagen.jpg);
    /* Se accede a la carpeta donde está la imagen.*/
}
```

Ejemplo 2: Por ruta externa

```css
body {
    background-image: url(https://img3.wallspic.com/previews/6/8/3/5/1/115386/115386-artes_creativas-personaje_de_ficcion-supervillano-criatura_sobrenatural-arte-x750.jpg);

    /* Se coloca el link de la imagen. */
}
```
- Acceder a la ```demo-02``` para ver un ejemplo sobre lo que comenté anteriromente.

<h3> 3. background-repeat: </h3>

* Esta propiedad nos permite repetir una imagen ya sea horizontal(x) o verticalmente(y)

```css
/* Repetir horizontal */
body {
    background-image: url(https://img3.wallspic.com/previews/6/8/3/5/1/115386/115386-artes_creativas-personaje_de_ficcion-supervillano-criatura_sobrenatural-arte-x750.jpg);

    background-repeat: repeat-x;
}
```

```css
/* Repetir vertical */
body {
    background-image: url(https://img3.wallspic.com/previews/6/8/3/5/1/115386/115386-artes_creativas-personaje_de_ficcion-supervillano-criatura_sobrenatural-arte-x750.jpg);

    background-repeat: repeat-y;
}
```

* Tambíen no podemos repetir dicha imagen.

```css
/* No repetir */
body {
    background-image: url(https://img3.wallspic.com/previews/6/8/3/5/1/115386/115386-artes_creativas-personaje_de_ficcion-supervillano-criatura_sobrenatural-arte-x750.jpg);

    background-repeat: no-repeat;
}
```
- Acceder a la ```demo-03``` para ver un ejemplo sobre lo que comenté anteriromente.

<h3> 4. background-position: </h3>

* Con esta propiedad, podemos especificar la posicion de nuestra imagen.

```css
body {
  background-image: url(../imagen/imagen01.png);
  background-repeat: no-repeat;
  background-position: right top; /* Posicion, esquina superior derecha
}
```
- Acceder a la ```demo-04``` para ver un ejemplo sobre lo que comenté anteriromente.

<h3> 5. background-attachment: </h3>

* Esta propiedad sirve para especificar si la imagen debe ser fija o desplazable.

* Fija: 
```css
body {
  background-image: url(../imagen/imagen01.png);
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```
* Desplazable:
```css
body {
  background-image: url(../imagen/imagen01.png);
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: scroll;
}
```
- Acceder a la ```demo-04``` para ver un ejemplo sobre lo que comenté anteriromente.

- NOTA: Desarrollar la homework.