# Margins (Márgenes)  en CSS

* La propiedad margin sirve para crear espacio alrededor de los elementos, fuera de los bordes definidos

<div style="text-align:center;">
    <img src="https://uniwebsidad.com/static/libros/imagenes/css/f0428.gif">
</div>

```css
margin-top: /* margen superior */
margin-right: /* margen derecho */
margin-bottom: /* margen inferior */
margin-left: /* margen izquierdo */
```
Ejemplo:

```css
h1 {
    margin-top: 20px;
    margin-right: 30px;
    margin-bottom: 20px;
    margin-left: 30px;
}
```
- Ver la ```demo-01```.

- En el ejemplo anterior vemos que las medidas de los márgenes son paralelas, esto se puede abreviar de la siguiente manera:

```css
h1 {
    margin: 20px 30px;
}
```
En conclusion los 20px del margen superior se heredan en el margen inferior, lo mismo pasa con los márgenes derecho eh izquierdo.

- Ver la ```demo-02```.

- Como ves obnenemos lo mismo que en la demo-01.

- Ahora si queremos abreviar aun más, podemos hacer lo siguiente.

```css
h1 {
    margin: 20px;
}
```

- Se hereda la medida de 20px a todos los márgenes.

- Ver la ```demo-03```.

* Ahora tambien podemos abreviar de la siguiente manera:

```css
h1 {
    margin: 20px 30px 40px 50px;
}
/*
El margin-top: 20px
El margin-right: 30px
El margin-bottom: 40px
El margin-left: 50px
*/
```

- Ver la ```demo-04```.

* El valor automático

```css
h1 {
    width: 300px;
    margin: auto;
    border: 1px solid red;
}

/*
Te permite centrar el elemento horizontalmente dentro de su contenedor
 */
```

- Ver la ```demo-05```.