# Lección 6: Creación de enlaces en HTML

## ¿Qué son los enlaces en HTML?

Los enlaces en HTML permiten conectar una página web con otros recursos, como:

- Otras páginas web.
- Documentos.
- Imágenes.
- Archivos.
- Diferentes secciones dentro de una misma página.

Los enlaces son elementos fundamentales en Internet porque permiten la navegación entre diferentes sitios y contenidos.

Para crear enlaces en HTML se utiliza la etiqueta `a`.

---

# Etiqueta a

La etiqueta `a` permite crear un enlace o hipervínculo dentro de una página web.

El contenido colocado dentro de esta etiqueta será el texto o elemento que el usuario podrá seleccionar para acceder al enlace.

### Ejemplo:

```html
<a href="https://www.google.com">
    Ir a Google
</a>
```

En este ejemplo:

- `a`: representa la etiqueta de enlace.
- `href`: indica la dirección a la que se dirigirá el usuario.
- `Ir a Google`: es el texto visible que podrá seleccionar el usuario.

---

# Atributo href

## ¿Qué es href?

El atributo `href` significa **Hypertext Reference** o referencia de hipertexto.

Este atributo indica la dirección o ubicación del recurso al que queremos acceder.

Es el atributo principal utilizado dentro de la etiqueta `a`.

---

## Ejemplo:

```html
<a href="https://www.youtube.com">
    Visitar YouTube
</a>
```

Cuando el usuario haga clic en el texto:

```
Visitar YouTube
```

será enviado a la página indicada dentro del atributo `href`.

---

# Tipos de enlaces en HTML

Existen diferentes tipos de enlaces que podemos crear:

- Enlaces externos.
- Enlaces internos.
- Enlaces a archivos.
- Enlaces mediante imágenes.

---

# Enlaces externos

## ¿Qué son?

Los enlaces externos permiten acceder a páginas que se encuentran en otro sitio web.

Normalmente utilizan una URL completa.

---

## Ejemplo:

```html
<a href="https://www.google.com">
    Buscar en Google
</a>
```

El navegador abrirá la página indicada en la dirección proporcionada.

---

# Enlaces internos

## ¿Qué son?

Los enlaces internos permiten navegar entre diferentes páginas dentro del mismo proyecto.

Son utilizados cuando una página web contiene varios archivos HTML.

---

## Ejemplo:

Estructura del proyecto:

```
Proyecto
│
├── index.html
│
├── contacto.html
│
└── servicios.html
```

Para acceder a otra página utilizamos:

```html
<a href="contacto.html">
    Contactarnos
</a>
```

Al hacer clic, el usuario será dirigido al archivo:

```
contacto.html
```

---

# Atributo target

## ¿Qué es target?

El atributo `target` permite definir dónde se abrirá el enlace.

Uno de los valores más utilizados es:

```
_blank
```

Este valor permite abrir el enlace en una nueva pestaña del navegador.

---

## Ejemplo:

```html
<a 
    href="https://www.youtube.com"
    target="_blank"
>
    Abrir YouTube
</a>
```

### Resultado:

- La página actual permanece abierta.
- El enlace se abre en una nueva pestaña.

---

# Valores del atributo target

Los valores más utilizados son:

| Valor | Descripción |
|---|---|
| `_blank` | Abre el enlace en una nueva pestaña |
| `_self` | Abre el enlace en la misma pestaña |
| `_parent` | Abre el enlace en el contexto superior |
| `_top` | Abre el enlace ocupando toda la ventana |

---

# Enlaces utilizando imágenes

También podemos convertir una imagen en un enlace.

Para esto debemos colocar la etiqueta `img` dentro de la etiqueta `a`.

---

## Ejemplo:

```html
<a href="https://www.google.com">

    <img 
        src="logo.png"
        alt="Logo de Google"
    >

</a>
```

Ahora la imagen funcionará como un botón que llevará al usuario al enlace indicado.

---

# Enlaces dentro de la misma página

HTML permite crear enlaces que permiten desplazarse hacia diferentes partes de una misma página.

Para esto utilizamos identificadores mediante el atributo `id`.

---

## Crear una sección:

```html
<h2 id="contacto">
    Contacto
</h2>
```

---

## Crear el enlace:

```html
<a href="#contacto">
    Ir a contacto
</a>
```

Cuando el usuario haga clic, la página se desplazará automáticamente hacia la sección indicada.

---

# Enlaces para enviar correos electrónicos

También podemos crear enlaces que abran automáticamente el programa de correo del usuario.

Para esto utilizamos:

```
mailto:
```

---

## Ejemplo:

```html
<a href="mailto:correo@gmail.com">
    Enviar correo
</a>
```

Al hacer clic en el enlace, se abrirá una aplicación de correo para enviar un mensaje.

---

# Enlaces para realizar llamadas

En páginas web adaptadas para dispositivos móviles podemos crear enlaces para realizar llamadas telefónicas.

Para esto utilizamos:

```
tel:
```

---

## Ejemplo:

```html
<a href="tel:+51999999999">
    Llamar ahora
</a>
```

Al seleccionar el enlace, el dispositivo intentará realizar una llamada al número indicado.

---

# Diferencia entre texto normal y enlace

| Texto normal | Enlace |
|---|---|
| Solo muestra información | Permite navegar hacia otro recurso |
| No tiene interacción | Puede ser seleccionado por el usuario |
| No utiliza `href` | Utiliza el atributo `href` |

---

# Buenas prácticas al crear enlaces

Al crear enlaces en HTML se recomienda seguir algunas buenas prácticas.

---

## Utilizar textos descriptivos

Los textos de los enlaces deben indicar claramente hacia dónde dirigirá al usuario.

### Ejemplo recomendado:

```html
<a href="servicios.html">
    Ver nuestros servicios
</a>
```

### Ejemplo no recomendado:

```html
<a href="servicios.html">
    Haz clic aquí
</a>
```

Un texto descriptivo mejora la experiencia del usuario.

---

## Revisar que los enlaces funcionen

Es importante verificar que:

- La dirección sea correcta.
- El archivo exista.
- No existan enlaces rotos.

---

## Usar target="_blank" correctamente

Cuando abrimos enlaces externos en nuevas pestañas podemos utilizar:

```html
target="_blank"
```

Esto permite mantener abierta la página actual mientras se visualiza el nuevo recurso.

---

# Ejemplo práctico

```html
<!DOCTYPE html>
<html>

<head>
    <title>Ejemplo de enlaces</title>
</head>

<body>

    <h1>Mis páginas favoritas</h1>

    <p>
        Puedes visitar los siguientes sitios:
    </p>

    <a href="https://www.google.com">
        Ir a Google
    </a>

    <br>

    <a 
        href="https://www.youtube.com"
        target="_blank"
    >
        Abrir YouTube en una nueva pestaña
    </a>

    <h2>
        Contacto
    </h2>

    <a href="mailto:correo@gmail.com">
        Enviar correo
    </a>

</body>

</html>
```

---

# Resultado esperado

La página mostrará:

- Un título principal.
- Un texto explicativo.
- Un enlace para acceder a Google.
- Un enlace que abrirá YouTube en una nueva pestaña.
- Un enlace para enviar un correo electrónico.

---

# Conclusión

Los enlaces en HTML permiten conectar diferentes recursos y mejorar la navegación dentro de una página web.

Para crear enlaces utilizamos la etiqueta `a`.

Los atributos principales son:

- `href`: indica la dirección del enlace.
- `target`: define dónde se abrirá el enlace.
- `id`: permite crear enlaces dentro de la misma página.

El uso correcto de enlaces permite crear páginas web más interactivas, organizadas y fáciles de navegar para los usuarios.