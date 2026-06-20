# Script - Lección 8: Colores, Fuentes y Alineación
 
## Colores en CSS
 
En CSS puedes definir colores de tres formas distintas. La más sencilla es usar el nombre del color en inglés:
 
```css
h1 {
    color: red;
}
```
 
También puedes usar códigos hexadecimales, que te permiten elegir cualquier color exacto. Son seis caracteres precedidos de un `#`:
 
```css
h1 {
    color: #3498db;
}
```
 
O puedes usar RGB, indicando cuánto rojo, verde y azul tiene el color (cada valor va de 0 a 255):
 
```css
h1 {
    color: rgb(52, 152, 219);
}
```
 
Para el fondo de un elemento usas `background-color` en lugar de `color`:
 
```css
body {
    background-color: #f0f0f0;
}
```
 
## Fuentes en CSS
 
La propiedad `font-family` cambia el tipo de letra. Puedes indicar varias opciones separadas por comas: si el navegador no tiene la primera, usará la siguiente:
 
```css
p {
    font-family: Arial, sans-serif;
}
```
 
Con `font-size` controlas el tamaño del texto. La unidad `px` significa píxeles:
 
```css
h1 {
    font-size: 36px;
}
 
p {
    font-size: 16px;
}
```
 
Con `font-weight` puedes poner el texto en negrita:
 
```css
h2 {
    font-weight: bold;
}
```
 
## Alineación del texto
 
La propiedad `text-align` controla cómo se alinea el texto dentro de su contenedor:
 
```css
h1 {
    text-align: center;
}
 
p {
    text-align: left;
}
```
 
Los valores posibles son `left`, `right`, `center` y `justify`.
 
## Bordes y espaciado
 
Con `border` puedes agregar un borde alrededor de cualquier elemento. Se define con el grosor, el estilo y el color:
 
```css
p {
    border: 2px solid black;
}
```
 
Con `padding` agregas espacio entre el contenido y el borde del elemento:
 
```css
p {
    padding: 10px;
}
```
 
## Ejemplo completo
 
Aquí tienes una página que combina todo lo aprendido en esta lección:
 
```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Página con Estilos</title>
    <style>
        body {
            background-color: #f9f9f9;
            font-family: Arial, sans-serif;
        }
 
        h1 {
            color: #2c3e50;
            font-size: 36px;
            text-align: center;
        }
 
        p {
            color: #555555;
            font-size: 16px;
            text-align: left;
            border: 1px solid #cccccc;
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1>Mi Página Personal</h1>
    <p>Hola, me llamo Alberto y estoy aprendiendo CSS.</p>
    <p>Con CSS puedo cambiar colores, fuentes y mucho más.</p>
</body>
</html>
```
 
## Puntos clave
 
* `color` cambia el color del texto; `background-color` cambia el fondo
* Los colores se pueden escribir con nombre en inglés, código hexadecimal `#` o RGB
* `font-family` cambia la fuente; `font-size` cambia el tamaño en píxeles
* `text-align` alinea el texto: `left`, `center`, `right` o `justify`
* `border` agrega un borde y `padding` agrega espacio interno al elemento
