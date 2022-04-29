#  Bordes en CSS

Sirven para especificar el estilo, el ancho y el color del borde de un elemento.

* Propiedad border-style: 
- Para el estilo del borde.

```css
                dotted;
                dashed;
                solid; 
                double;
                groove;
border-style:
                ridge;
                inset;
                outset;
                none;
                hidden;
```

1. Borde dotted:
```css
border-style: dotted;
```
2. Borde dashed:
```css
border-style: dashed;
```
3. Borde solid:
```css
border-style: solid;
```
4. Borde double:
```css
border-style: double;
```
5. Borde groove:
```css
border-style: groove;
```
6. Borde ridge:
```css
border-style: ridge;
```
7. Borde inset:
```css
border-style: inset;
```
8. Borde outset:
```css
border-style: outset;
```
9. Borde none:
```css
border-style: none;
```
10. Borde hidden:
```css
border-style: hidden;
```
11. Borde mixed:
```css
border-style: dotted dashed solid double;
```

- Ver todo esto en la ```demo```.

* Propiedad border-width:
- Para el ancho del borde. 

- Ejemplos de anchos de borde.

```css
h2.one {
  border-style: solid;
  border-width: 5px;
}

h2.two {
  border-style: solid;
  border-width: medium;
}

h2.three {
  border-style: dotted;
  border-width: 2px;
}

h2.four {
  border-style: dotted;
  border-width: thick;
}
```
- Ver la ```demo-01 ```.

- Anchos laterales especificos.

```css
p.one {
  border-style: solid;
  border-width: 5px 20px; /* 5px top and bottom, 20px on the sides */
}

p.two {
  border-style: solid;
  border-width: 20px 5px; /* 20px top and bottom, 5px on the sides */
}

p.three {
  border-style: solid;
  border-width: 25px 10px 4px 35px; /* 25px top, 10px right, 4px bottom and 35px left */
}
```

- Ver la ```demo-02 ```.

* Propiedad border-color:
- Para el color del borde.

Ejemplo

```css
h2.one {
  border-style: solid;
  border-color: red;
}

h2.two {
  border-style: solid;
  border-color: green;
}

h2.three {
  border-style: dotted;
  border-color: blue;
}
```

- Ver la ```demo-03```.

* Propiedad border-radius:
- Para redondear los bordes.

Ejemplo:

```css
h2.round {
  border: 2px solid red;
  border-radius: 8px;
  padding: 5px;
}
```

- Ver la ```demo-04```.