# Lección 9: Creando tu página de perfil

## Uniendo todas las piezas
Durante el curso aprendimos que HTML es la estructura (los ladrillos)
y CSS es el diseño (la pintura). Ahora vamos a unir ambos para crear
una página de perfil completa. Por ejemplo, vamos a crear el perfil
de un estudiante amante de la tecnología.

## Estructura base con HTML
Primero, armamos el esqueleto en nuestro archivo HTML. Usaremos un
título, una imagen, un párrafo de presentación y una lista para sus pasatiempos:

    <h1>¡Hola! Soy Alex </h1>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/A_black_background_with_computer_code.jpg/400px-A_black_background_with_computer_code.jpg" alt="Código">
    <p>Soy un estudiante. ¡Me encanta la tecnología y la ciencia ficción!</p>
    <ul>
        <li>Aprender programación</li>
        <li>Jugar videojuegos</li>
    </ul>

Si vemos esto, será una página blanca con letras negras. Muy básica,
ya que solo tenemos la estructura de la información.

## Aplicando la magia del CSS
Para que se vea como un perfil real, vamos a nuestro archivo CSS.
Le daremos un fondo oscuro a la página, centraremos el texto
y haremos que la imagen sea completamente redonda:

    body {
        background-color: #1a1a2e;
        color: white;
        text-align: center;
    }

    img {
        width: 250px;
        border-radius: 50%;
        border: 5px solid #00d2ff;
    }

## El resultado final
Al aplicar estos estilos, nuestro perfil cobra vida. La imagen
se vuelve un círculo perfecto gracias a la propiedad border-radius de 50%,
y el fondo oscuro hace que el texto blanco resalte. ¡Ya tienes tu
primera página web real!

