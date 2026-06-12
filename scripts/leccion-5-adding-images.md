# Lección 5: Añadiendo Imágenes en HTML

## ¿Qué son las imágenes en una página web?

Las imágenes son elementos visuales que permiten hacer una página web más atractiva y fácil de entender.

Se utilizan para mostrar fotografías, ilustraciones, logotipos, gráficos y cualquier contenido visual.

Ejemplos:

* Fotografías
* Logotipos
* Dibujos
* Iconos

## La etiqueta img

Para insertar una imagen en HTML utilizamos la etiqueta `img`.

Su estructura básica es:

```html
<img src="imagen.jpg">
```

La etiqueta `img` le indica al navegador que debe mostrar una imagen en la página.

## El atributo src

El atributo `src` significa *source* (fuente u origen).

Sirve para indicar la ubicación de la imagen que queremos mostrar.

Ejemplo:

```html
<img src="perro.jpg">
```

También podemos utilizar una dirección de internet:

```html
<img src="https://ejemplo.com/perro.jpg">
```

## El atributo alt

El atributo `alt` significa texto alternativo.

Su función es describir la imagen cuando esta no puede mostrarse correctamente.

Ejemplo:

```html
<img src="perro.jpg" alt="Perro feliz">
```

Beneficios del atributo `alt`:

* Describe la imagen.
* Mejora la accesibilidad.
* Ayuda cuando la imagen no carga.

## Estructura completa de una imagen

```html
<img src="perro.jpg" alt="Perro feliz">
```

Donde:

* `img` inserta la imagen.
* `src` indica la ubicación.
* `alt` proporciona una descripción.

## Ejemplo práctico

```html
<h1>Mi Animal Favorito</h1>

<p>
El perro es uno de los animales más queridos del mundo.
</p>

<img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?w=600"
alt="Perro feliz">

<h2>¿Por qué me gustan los perros?</h2>

<p>
Porque son amigables, leales y excelentes compañeros.
</p>
```

## Resultado esperado

La página mostrará:

* Un título principal.
* Un párrafo descriptivo.
* Una imagen.
* Un subtítulo.
* Un párrafo adicional.

## Buenas prácticas

* Utilizar siempre el atributo `alt`.
* Elegir imágenes relacionadas con el contenido.
* Utilizar nombres descriptivos para las imágenes.
* Verificar que la ruta de la imagen sea correcta.

## Conclusión

Las imágenes permiten hacer páginas web más visuales e interesantes.

La etiqueta `img` se utiliza para insertar imágenes, mientras que el atributo `src` indica dónde se encuentra la imagen y el atributo `alt` proporciona una descripción alternativa.
