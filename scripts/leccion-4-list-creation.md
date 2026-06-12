# Lección 4: Creación de listas

## ¿Qué son las listas?

Las listas en HTML permiten estructurar colecciones de elementos relacionados en forma de enumeraciones ordenadas o desordenadas.

## Tipos de listas

### Listas ordenadas (Ordered Lists):

Una ordered list (lista ordenada) inicia con la etiqueta `ol`. Cada elemento de la lista inicia con la etiqueta `li`. El browser marca cada elemento de la lista con un número secuencial.

### Ejemplo de una lista ordenada:

```html
<ol>
  <li>Primer elemento</li>
  <li>Segundo elemento</li>
  <li>Tercer elemento</li>
</ol>
```

### Listas no ordenadas (Unordered Lists):

Las unordered lists (listas no ordenadas) inician con la etiqueta `ul`. Cada list item inicia con la etiqueta `li`. Por defecto, el browser marca con bullets (viñetas) cada elemento de la lista.

### Ejemplo de una lista no ordenada:

```html
<ul>
  <li>Primer elemento</li>
  <li>Segundo elemento</li>
  <li>Tercer elemento</li>
</ul>
```

### Diferencias:

Al hacer una lista no ordenada, se termina listado con puntos, mientras que al hacer una lista ordenada, se termina listado con números.

## Ejemplo práctico:

```html
<ul>
    <li>Emiliano Martínez</li>
    <li>Lionel Messi</li>
</ul>
<ol>
    <li>Argentina 1978</li>
    <li>México 1986</li>
    <li>Catar 2022</li>
</ol>
```

## Resultado esperado:

La página mostrará:
* Una lista de algunos jugadores de la selección argentina de fútbol, con viñetas.
* Una lista de los mundiales ganados por la selección argentina, con números.

## Conclusión:

Recordemos que las listas no ordenadas inician con la etiqueta ul, mientras que las listas ordenadas inician con las etiquetas ol, al mismo tiempo que cada vez que se quiere listar algo, hay que usar la etiqueta li.
