# Lección 2: Tu Primera Página HTML

## ¿Qué es un documento HTML?

Un documento HTML es un archivo de texto con instrucciones especiales que el navegador puede leer y convertir en una página web visual.

Cuando abres un sitio web, el navegador descarga uno o varios documentos HTML y los interpreta para mostrarte el contenido en pantalla.

## La estructura básica de HTML

Todo documento HTML válido sigue la misma estructura base.

Esta estructura tiene tres etiquetas fundamentales:

* `html`
* `head`
* `body`

## La etiqueta html

```html
<html>

</html>
```

La etiqueta `html` es el contenedor principal de todo el documento.

Todo el contenido de la página debe estar dentro de estas dos etiquetas.

La etiqueta de apertura es `<html>` y la de cierre es `</html>`.

## La etiqueta head

```html
<head>

</head>
```

La etiqueta `head` contiene información de configuración de la página.

Esta información no se muestra directamente en la pantalla, pero es muy importante.

Dentro del `head` colocamos el título de la página con la etiqueta `title`.

### La etiqueta title

```html
<title>Mi Primera Página</title>
```

El texto dentro de `title` aparece en la pestaña del navegador.

## La etiqueta body

```html
<body>

</body>
```

La etiqueta `body` contiene todo el contenido visible de la página.

Todo lo que el usuario puede ver en el navegador va dentro del `body`:

* Títulos
* Párrafos
* Imágenes
* Botones

## La declaración DOCTYPE

```html
<!DOCTYPE html>
```

Esta línea siempre va al inicio del documento.

Le indica al navegador que el archivo usa HTML moderno (HTML5).

## Estructura completa de un documento HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Primera Página</title>
</head>
<body>

    <h1>¡Hola, Mundo!</h1>
    <p>Esta es mi primera página web.</p>

</body>
</html>
```

Donde:

* `<!DOCTYPE html>` declara el tipo de documento.
* `<html>` envuelve todo el contenido.
* `<head>` contiene la configuración (como el título).
* `<body>` contiene el contenido visible.

## Las etiquetas de encabezado

HTML tiene seis niveles de encabezado para organizar el contenido:

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Sección de tercer nivel</h3>
```

El `h1` es el más grande e importante. El `h6` es el más pequeño.

## La etiqueta de párrafo

```html
<p>Este es un párrafo de texto.</p>
```

La etiqueta `p` se usa para escribir bloques de texto como párrafos.

## Ejemplo práctico

Escribe el siguiente código en CodePen:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Primera Página Web</title>
</head>
<body>

    <h1>¡Hola, Mundo!</h1>
    <p>Esta es mi primera página HTML. La creé aprendiendo desarrollo web.</p>

    <h2>¿Qué aprendí hoy?</h2>
    <p>Aprendí que una página HTML tiene tres partes: html, head y body.</p>

</body>
</html>
```

## Resultado esperado

La página mostrará:

* Un título principal grande que dice "¡Hola, Mundo!".
* Un párrafo descriptivo debajo.
* Un subtítulo secundario.
* Un segundo párrafo explicativo.

## Apertura y cierre de etiquetas

La mayoría de las etiquetas HTML tienen una etiqueta de apertura y una de cierre.

```html
<h1>Este es el contenido</h1>
```

* La etiqueta de apertura es `<h1>`.
* La etiqueta de cierre es `</h1>` (lleva una barra diagonal `/`).

Siempre debes cerrar las etiquetas que abres.

## Buenas prácticas

* Usar siempre `<!DOCTYPE html>` al inicio del documento.
* Indentar el código para que sea más fácil de leer.
* Cerrar todas las etiquetas que se abren.
* Escribir el título de la página en la etiqueta `title`.

## Conclusión

La estructura básica de HTML con `html`, `head` y `body` es la base de cualquier página web.

Una vez que domines esta estructura, podrás agregar todo tipo de contenido: imágenes, enlaces, listas, formularios y mucho más.

En la siguiente lección exploraremos cómo dar estilo a este contenido usando CSS.