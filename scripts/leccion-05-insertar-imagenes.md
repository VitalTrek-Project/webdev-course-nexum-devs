# Lección 5: Inserción de imágenes

## ¿Qué son las imágenes en HTML?

Las imágenes en HTML permiten agregar elementos visuales dentro de una página web, como fotografías, ilustraciones, logos o gráficos.

Estas imágenes ayudan a complementar la información de una página, haciendo que el contenido sea más atractivo, dinámico y fácil de entender para los usuarios.

Para insertar una imagen dentro de una página HTML se utiliza la etiqueta `img`.

---

# Etiqueta img

La etiqueta `img` permite mostrar una imagen dentro de una página web.

A diferencia de otras etiquetas HTML, la etiqueta `img` no necesita una etiqueta de cierre.

### Ejemplo:

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

La etiqueta `img` utiliza diferentes atributos que permiten configurar la imagen y definir sus características.

---

# Atributos de la etiqueta img

Los atributos permiten agregar características adicionales a una etiqueta HTML.

Los atributos más utilizados en la etiqueta `img` son:

- `src`
- `alt`
- `width`
- `height`

---

# Atributo src

## ¿Qué es src?

El atributo `src` significa **source** o fuente.

Este atributo indica la ubicación de la imagen que queremos mostrar dentro de nuestra página web.

La ubicación puede ser:

- Una imagen guardada dentro del proyecto.
- Una imagen obtenida desde Internet mediante una URL.

---

# Imagen almacenada dentro del proyecto

Cuando una imagen se encuentra dentro de nuestro proyecto, utilizamos el nombre del archivo o la ruta donde está ubicada.

### Ejemplo:

```html
<img src="perro.jpg">
```

El navegador buscará un archivo llamado:

```
perro.jpg
```

dentro de la misma carpeta donde se encuentra el archivo HTML.

---

# Imagen dentro de una carpeta

También podemos organizar nuestras imágenes dentro de carpetas para mantener ordenado el proyecto.

### Ejemplo de estructura:

```
Proyecto HTML
│
├── index.html
│
└── imagenes
    └── perro.jpg
```

Para acceder a la imagen utilizamos:

```html
<img src="imagenes/perro.jpg">
```

---

# Imagen desde Internet

También podemos insertar imágenes utilizando una dirección URL.

Una URL es una dirección que permite acceder a un recurso disponible en Internet.

### Ejemplo:

```html
<img src="https://pagina.com/perro.jpg">
```

El navegador utilizará esa dirección para buscar y mostrar la imagen automáticamente.

---

# Atributo alt

## ¿Qué es alt?

El atributo `alt` significa **alternative text** o texto alternativo.

Este atributo permite agregar una descripción de la imagen.

---

## Importancia del atributo alt

El atributo `alt` es importante porque:

- Permite describir el contenido de una imagen.
- Aparece cuando la imagen no puede cargarse correctamente.
- Ayuda a personas que utilizan lectores de pantalla.
- Mejora la accesibilidad de una página web.

---

## Ejemplo:

```html
<img 
    src="perro.jpg" 
    alt="Perro jugando en el parque"
>
```

Si la imagen no carga correctamente, el usuario podrá visualizar el texto:

```
Perro jugando en el parque
```

---

# Atributo width

## ¿Qué es width?

El atributo `width` permite modificar el ancho de una imagen.

Normalmente, su valor se establece en píxeles.

### Ejemplo:

```html
<img 
    src="perro.jpg"
    width="300"
>
```

La imagen tendrá un ancho de:

```
300 píxeles
```

---

# Atributo height

## ¿Qué es height?

El atributo `height` permite modificar la altura de una imagen.

### Ejemplo:

```html
<img 
    src="perro.jpg"
    height="200"
>
```

La imagen tendrá una altura de:

```
200 píxeles
```

---

# Uso combinado de width y height

Podemos utilizar ambos atributos al mismo tiempo para establecer un tamaño específico.

### Ejemplo:

```html
<img 
    src="perro.jpg"
    alt="Perro feliz"
    width="400"
    height="300"
>
```

En este ejemplo:

- El ancho de la imagen será de `400 píxeles`.
- La altura de la imagen será de `300 píxeles`.

---

# Formatos de imágenes utilizados en HTML

Existen diferentes formatos de imágenes que pueden utilizarse dentro de una página web.

---

## JPG o JPEG

### Características:

- Utilizado principalmente para fotografías.
- Tiene buena calidad visual.
- Permite reducir el tamaño del archivo.
- Es uno de los formatos más utilizados en páginas web.

### Ejemplo:

```
foto.jpg
```

---

## PNG

### Características:

- Permite utilizar fondos transparentes.
- Mantiene una buena calidad de imagen.
- Es utilizado para logos e íconos.

### Ejemplo:

```
logo.png
```

---

## GIF

### Características:

- Permite crear imágenes animadas.
- Utilizado para pequeñas animaciones.
- Soporta movimientos dentro de la imagen.

### Ejemplo:

```
animacion.gif
```

---

## SVG

### Características:

- Utiliza gráficos vectoriales.
- Puede cambiar de tamaño sin perder calidad.
- Es utilizado principalmente para logos e íconos.

### Ejemplo:

```
icono.svg
```

---

# Buenas prácticas al utilizar imágenes

Al trabajar con imágenes dentro de una página web se recomienda seguir algunas buenas prácticas.

---

## Utilizar siempre el atributo alt

Ejemplo correcto:

```html
<img src="gato.jpg" alt="Gato sentado">
```

Esto permite que la imagen tenga una descripción alternativa.

---

## Utilizar nombres descriptivos

Los nombres de los archivos deben explicar el contenido de la imagen.

### Ejemplo recomendado:

```
perro-jugando.jpg
```

### Ejemplo no recomendado:

```
imagen123.jpg
```

---

## Organizar las imágenes del proyecto

Una estructura ordenada facilita el mantenimiento del proyecto.

### Ejemplo:

```
Proyecto
│
├── index.html
│
├── css
│   └── styles.css
│
└── images
    ├── logo.png
    └── perro.jpg
```

---

## Optimizar el tamaño de las imágenes

Las imágenes con demasiado peso pueden provocar que una página web cargue lentamente.

Se recomienda:

- Comprimir las imágenes.
- Utilizar formatos adecuados.
- Evitar imágenes con tamaños innecesariamente grandes.

---

# Diferencia entre una imagen local y una imagen externa

| Imagen local | Imagen externa |
|-------------|----------------|
| Se encuentra dentro del proyecto | Se encuentra en Internet |
| Utiliza una ruta relativa | Utiliza una URL completa |
| No depende de otro servidor | Depende del servidor externo |

---

# Ejemplo práctico

```html
<!DOCTYPE html>
<html>

<head>
    <title>Mi Animal Favorito</title>
</head>

<body>

    <h1>El Perro</h1>

    <p>
        El perro es uno de los animales más queridos del mundo.
    </p>

    <img 
        src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg"
        alt="Perro feliz"
        width="400"
        height="300"
    >

    <h2>¿Por qué me gustan los perros?</h2>

    <p>
        Porque son animales amigables, leales y excelentes compañeros.
    </p>

</body>

</html>
```

---

# Resultado esperado

La página mostrará:

- Un título principal con el nombre del animal.
- Un texto descriptivo sobre el perro.
- Una imagen debajo del texto.
- Un segundo título con información adicional.
- Un párrafo explicando las características del animal.

---

# Conclusión

Las imágenes son elementos fundamentales dentro de una página web porque permiten complementar la información y mejorar la experiencia del usuario.

Para insertar imágenes utilizamos la etiqueta `img`.

Los atributos principales son:

- `src`: indica la ubicación de la imagen.
- `alt`: agrega una descripción alternativa.
- `width`: modifica el ancho.
- `height`: modifica la altura.

El correcto uso de imágenes permite crear páginas web más atractivas, organizadas y accesibles para todos los usuarios.