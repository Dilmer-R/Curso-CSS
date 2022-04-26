# Selectores de CSS

Se utilizan para seleccionar los elementos que se desea dar estilos.


<h3>Tipos o categorías de selectores en css:</h3>

* Selector Universal.

Ejemplo:

```css
* {
    margin: 0;
    padding: 0;
}
```

* Simples: Seleccionan los elementos de nombre, id y clase.

<h3>El de elementos:</h3>

```css
/* Seleccinamos el elemento p */

p {
  text-align: center;
  color: red;
}

```
<h3>El de ID:</h3>

```css
/* Seleccionamos el elemento con atributo id que es para1 */

#para1 {
  text-align: center;
  color: red;
}

```
<h3>El de CLASE:</h3>

```css

/* Seleccionamos el elemento con clase center */

.center {
  text-align: center;
  color: red;
}

```

* Selector de agrupación.

Este ocupa en todos los elementos que tengan las mismas propiedades.

<h3> Ejemplo:</h3>

```css

h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}

```

* Para esto, lo más conveniente es agrupar los selectores.

<h3> Ejemplo:</h3>

```css

/* Para agrupar se utiliza "," */

h1, h2, p {
  text-align: center;
  color: red;
}

```

- NOTA: Desarrollar la homework.