
# Lección 10: Errores comunes y próximos pasos

## ¿Qué es un "bug"?
En la programación, a los errores les decimos "bugs". Es completamente
normal que al escribir código la página se vea mal o se rompa.
No te asustes, resolver problemas es la tarea principal de
un desarrollador web. Veamos los errores más típicos.

## Etiquetas HTML sin cerrar
Uno de los errores más comunes es abrir una etiqueta y olvidar
la barra inclinada para cerrarla. Por ejemplo, si olvidas cerrar un h1:

    <h1>¡Hola! Soy Alex 
    <p>Soy un estudiante...</p>

El navegador pensará que el párrafo también es parte del título
y hará todo el texto de la página gigante. Siempre asegúrate de 
poner </h1> al final.

## Olvidar el punto y coma en CSS
En CSS, cada instrucción debe terminar con un punto y coma.
Es como el punto final de una oración. Si lo omites, el navegador
no entenderá dónde termina el color y empieza el resto de reglas:

    body {
        background-color: #1a1a2e
        color: white;
    }

En este caso, el color de fondo no funcionará porque le falta
el punto y coma a la línea de arriba. Un solo símbolo hace 
toda la diferencia.

## Herramientas para seguir aprendiendo
Para evitar estos errores, los programadores usamos validadores.
La herramienta "W3C Validator" lee tu código y te avisa si olvidaste
cerrar algo. Además, si tienes dudas sobre una etiqueta, busca
"MDN Web Docs" en Google, es el diccionario oficial de la web.

## Comparte tu trabajo
¡Felicidades por terminar el curso! Toma el enlace de tu editor 
y compártelo con nosotros en el formulario. Sigue practicando, 
cambia los colores, agrega tus fotos y nunca dejes de programar.