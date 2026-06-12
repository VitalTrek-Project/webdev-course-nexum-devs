# Lección 6: Conectando la Web con Enlaces

## ¿Qué es un enlace?

Un enlace (o hipervínculo) es un elemento que permite navegar hacia otra página web, un documento o una sección específica.

Los enlaces son la base de la navegación en Internet.

Ejemplos:

* Ir a Google.
* Abrir YouTube.
* Acceder a una red social.
* Visitar otra página de un sitio web.

## La etiqueta a

Para crear enlaces en HTML utilizamos la etiqueta `a`.

Su estructura básica es:

```html
<a href="https://www.google.com">Ir a Google</a>
```

La etiqueta `a` indica que estamos creando un enlace.

## El atributo href

El atributo `href` significa *Hypertext Reference*.

Sirve para indicar la dirección a la que se dirigirá el usuario al hacer clic.

Ejemplo:

```html
<a href="https://www.youtube.com">Ir a YouTube</a>
```

## Texto del enlace

El texto que se encuentra entre la etiqueta de apertura y cierre será visible para el usuario.

Ejemplo:

```html
<a href="https://www.google.com">Buscar en Google</a>
```

En este caso, el usuario verá:

Buscar en Google

## Abrir enlaces en una nueva pestaña

Podemos utilizar el atributo `target="_blank"`.

Ejemplo:

```html
<a href="https://www.google.com" target="_blank">
    Abrir Google
</a>
```

Esto abrirá la página en una nueva pestaña.

## Ejemplo práctico

```html
<h1>Mis sitios web favoritos</h1>

<p>
Haz clic en los siguientes enlaces para visitar mis páginas favoritas.
</p>

<a href="https://www.youtube.com">
    Ir a YouTube
</a>

<br><br>

<a href="https://www.google.com">
    Ir a Google
</a>
```

## Buenas prácticas

* Utilizar textos descriptivos.
* Verificar que las direcciones sean correctas.
* Evitar enlaces rotos.
* Utilizar `target="_blank"` cuando sea necesario abrir otra página.

## Conclusión

Los enlaces permiten conectar páginas web y navegar por Internet.

La etiqueta `a` crea el enlace y el atributo `href` indica la dirección de destino.
