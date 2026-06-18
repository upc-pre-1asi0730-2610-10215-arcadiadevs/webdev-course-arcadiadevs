# Lección 3: Organizando la Información

_(Contenido para los instructores)_

## 1. Estructura de Carpetas (GitHub)

```text
/starter-files/lesson-03        # Carpeta con el codigo base para la clase
└── index.html
/completed-examples/lesson-03   # El código completo de la lección
└── index.html
```

## 2. Ficha Técnica

- **Duración estimada:** 8 minutos.
- **Objetivo de aprendizaje:** Organizar información en una página web utilizando encabezados jerárquicos (`<h1>` a `<h6>`), párrafos (`<p>`) y listas ordenadas y desordenadas (`<ol>`, `<ul>`).

## 3. Guion de Video (8 minutos)

> **[Escena 1: Introducción]**
> - **Visual:** Pantalla con un bloque de texto gigante sin títulos ni estructura. Se resalta lo difícil de leer.
> - **Voz en off (Audio):** "¡Hola! Imagina leer un libro que no tiene títulos, capítulos ni separación entre párrafos. Sería muy difícil de entender, ¿verdad? Lo mismo pasa en las páginas web. Hoy aprenderemos a organizar nuestra información para que todos puedan leerla fácilmente."
>
> **Bloque A: ¿Cómo leemos una página? (45-60 segundos)**
> - **Visual:** Comparación lado a lado: página desordenada vs. página con títulos y listas.
> - **Voz en off (Audio):** "Antes de escribir código, pensemos en cómo leemos una página. Si todo aparece en un solo bloque gigante, el visitante se cansa rápido y no sabe por dónde empezar. En cambio, cuando usamos títulos, párrafos y listas, la información se vuelve más fácil de explorar. Organizar no significa decorar; significa darle estructura al contenido."
>
> **[Escena 2: Los Encabezados]**
> - **Visual:** En CodePen se escriben `<h1>`, `<h2>`, `<h3>` con diferentes textos. Se muestra la diferencia visual de tamaño.
> - **Voz en off (Audio):** "Para crear títulos, usamos las etiquetas `<h1>` hasta `<h6>`. El `<h1>` es el título principal, el más grande, y solo debe haber uno por página. Los `<h2>` y `<h3>` son como subtítulos. Lo importante es no elegir el encabezado solo porque se ve más grande, sino por la importancia del contenido."
>
> **[Escena 3: Los Párrafos]**
> - **Visual:** Se escribe un `<p>` debajo de un `<h2>`. Se muestra cómo el título presenta la idea y el párrafo la explica.
> - **Voz en off (Audio):** "El párrafo `<p>` sirve para desarrollar una idea. Por ejemplo, si el encabezado dice 'Mis Películas Favoritas', el párrafo puede explicar por qué te gusta ese tema. Los encabezados guían; los párrafos cuentan."
>
> **[Escena 4: Las Listas]**
> - **Visual:** Se escriben una lista `<ul>` con viñetas y una lista `<ol>` con números.
> - **Voz en off (Audio):** "¿Y si queremos hacer una lista? ¡Tenemos dos opciones! Si el orden no importa, como una lista de compras, usamos `<ul>` (lista desordenada) y colocamos viñetas. Si el orden es clave, como los pasos de un tutorial, usamos `<ol>` (lista ordenada) que nos dará números. Cada elemento se escribe con `<li>`."
>
> **Bloque E: Ahora es tu turno (60-75 segundos)**
> - **Visual:** Pantalla con texto: "Reto: Escribe tres elementos en tu lista". Temporizador de 20 segundos.
> - **Voz en off (Audio):** "Ahora es tu turno. Escribe tres elementos dentro de tu lista. Pueden ser tres películas, tres videojuegos o tres metas. Recuerda: la lista es la caja grande, y cada elemento individual va dentro de una etiqueta `<li>`. Cuando termines, revisa si cada elemento tiene apertura y cierre."
>
> **Bloque F: Errores comunes (45-60 segundos)**
> - **Visual:** Se muestra un `<li>` fuera de una lista y se marca como error.
> - **Voz en off (Audio):** "Un error común es escribir elementos `<li>` fuera de una lista. Recuerda que los `<li>` deben estar dentro de `<ul>` o `<ol>`. Otro error es usar un encabezado para escribir un texto largo. Si es una explicación, usa `<p>`."
>
> **Bloque G: Cierre (30-45 segundos)**
> - **Visual:** Resumen en tarjetas: encabezados = títulos, párrafos = explicaciones, listas = elementos.
> - **Voz en off (Audio):** "Hoy aprendiste a darle estructura a tu página con encabezados, párrafos y listas. En la siguiente lección añadiremos imágenes y enlaces para conectar nuestra página con el resto del mundo."

## 4. Sugerencias Multimedia

- **Anotaciones en Pantalla:** Mostrar la jerarquía de encabezados como una pirámide o escalera visual.
- **Resaltado de Sintaxis:** Resaltar en colores diferentes las etiquetas `<h1>`, `<h2>`, `<p>`, `<ul>`, `<ol>`, `<li>`.
- **Transiciones:** Transición animada al pasar de la página desordenada a la organizada.
