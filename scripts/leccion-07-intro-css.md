# Script - Lección 7: Introducción a CSS
 
## ¿Qué es CSS?
 
CSS significa *Cascading Style Sheets* (Hojas de Estilo en Cascada). Mientras HTML define el contenido de una página web, CSS se encarga de su apariencia: colores, tamaños, fuentes, posiciones y mucho más.
 
Sin CSS una página web es como un documento de texto plano. Con CSS se convierte en algo visual y atractivo.
 
## Cómo conectar CSS a tu HTML
 
Hay varias formas de usar CSS. La más ordenada es crear un archivo `.css` separado y enlazarlo desde el HTML usando la etiqueta `<link>` dentro del `<head>`:
 
```html
<head>
    <title>Mi Página</title>
    <link rel="stylesheet" href="styles.css">
</head>
```
 
También puedes escribir CSS directamente dentro del HTML usando la etiqueta `<style>` en el `<head>`:
 
```html
<head>
    <style>
        body {
            background-color: lightblue;
        }
    </style>
</head>
```
 
Para practicar en esta lección usaremos la etiqueta `<style>` para que todo quede en un solo archivo.
 
## Cómo funciona una regla CSS
 
Una regla CSS tiene dos partes: el **selector** y las **propiedades**. El selector indica a qué elemento HTML se le aplica el estilo, y las propiedades definen cómo se verá:
 
```css
selector {
    propiedad: valor;
}
```
 
Por ejemplo, para cambiar el color de fondo de toda la página:
 
```css
body {
    background-color: lightblue;
}
```
 
## Selectores básicos
 
Los selectores más comunes que usarás son:
 
* **Selector de etiqueta**: aplica el estilo a todos los elementos de ese tipo
 
```css
h1 {
    color: red;
}
```
 
* **Selector de clase**: aplica el estilo a los elementos que tengan esa clase. En HTML se escribe con `class="nombre"` y en CSS con un punto antes del nombre:
 
```css
.titulo-principal {
    color: blue;
}
```
 
```html
<h1 class="titulo-principal">Bienvenido</h1>
```
 
## Tu primera página con estilo
 
Aquí tienes un ejemplo completo con HTML y CSS juntos:
 
```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Primera Página con Estilo</title>
    <style>
        body {
            background-color: lightyellow;
        }
 
        h1 {
            color: darkblue;
        }
 
        p {
            color: gray;
        }
    </style>
</head>
<body>
    <h1>Hola, soy Alberto</h1>
    <p>Esta es mi primera página con estilos CSS.</p>
</body>
</html>
```
 
Fíjate que cada propiedad CSS termina con punto y coma `;`, igual que en Java.
 
## Puntos clave
 
* CSS controla la apariencia visual de tu página web
* Se conecta al HTML con `<link>` o se escribe directamente con `<style>`
* Una regla CSS tiene un selector y propiedades con sus valores
* `body` aplica estilos a toda la página
* Los selectores de etiqueta afectan a todos los elementos de ese tipo
* Los selectores de clase se identifican con un punto: `.nombre-de-clase`
