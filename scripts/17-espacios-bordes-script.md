# Lección 7: Espacios y Bordes

_(Contenido para los instructores)_

## 1. Estructura de Carpetas (GitHub)

```text
/starter-files/lesson-07        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-07   # El código completo de la lección
├── index.html
└── styles.css
```

## 2. Ficha Técnica

- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Comprender el modelo de caja (box model) usando `div`, `border`, `padding` y `margin`, y aplicar la técnica `margin: auto` para centrar bloques.

## 3. Guion de Video (8 minutos)

> **[Escena 1: Introducción]**
> - **Visual:** Pantalla con una página donde todo el texto está pegado a los bordes. Se resalta lo apretado que se ve.
> - **Voz en off (Audio):** "Nuestra aplicación va tomando forma, pero tiene un problema: todo está pegado a los bordes. ¡Nuestros textos necesitan respirar! Hoy aprenderemos a darle espacio a las cosas y a ponerles marcos."
>
> **Bloque A: ¿Qué es un div? (45-60 segundos)**
> - **Visual:** Se escribe un `<div>` que envuelve un `<h1>` y un `<p>`. Se dibuja un recuadro alrededor.
> - **Voz en off (Audio):** "Antes de hablar de bordes y espacios, veamos esta etiqueta: `<div>`. Un div es como una caja o contenedor que nos permite agrupar varios elementos. Gracias a eso, podemos aplicar estilos a toda la caja completa."
>
> **[Escena 2: La Teoría de las Cajas]**
> - **Visual:** Se agrega `border: 2px solid black;` al div. Aparece el borde negro. Luego se agrega `padding: 20px;` y el contenido se separa del borde.
> - **Voz en off (Audio):** "En la web, absolutamente todo es una caja invisible. Para ver estas cajas, pongamos un borde con `border: 2px solid black;`. El `2px` indica el grosor, `solid` el tipo de línea, y `black` el color. Pero el texto está tocando el borde. Para darle espacio interior, usamos `padding: 20px;`."
>
> **[Escena 3: Margen (Espacio Exterior)]**
> - **Visual:** Se agrega `margin-top: 30px;` y la caja se separa del elemento de arriba.
> - **Voz en off (Audio):** "¿Y qué pasa si queremos alejar nuestra caja de las demás? Usamos el margen o `margin`. Mientras que el padding empuja hacia adentro, el margen empuja hacia afuera. Si le ponemos `margin-top: 30px;`, le estamos diciendo: '¡Aléjate 30 píxeles para arriba!'."
>
> **[Escena 4: El Truco de Centrar Bloques]**
> - **Visual:** Se escribe `width: 50%;` y `margin: auto;`. La caja se centra en pantalla.
> - **Voz en off (Audio):** "Te enseñaremos uno de los trucos más valiosos. Para centrar toda una caja en medio de la pantalla, primero le damos un ancho fijo con `width: 50%;`. Luego aplicamos la magia: `margin: auto;`. Esto le dice al navegador que reparta el espacio sobrante equitativamente a los lados."
>
> **Bloque E: Ahora es tu turno (60-75 segundos)**
> - **Visual:** Pantalla con texto: "Reto: Cambia el width". Temporizador de 20 segundos.
> - **Voz en off (Audio):** "Ahora es tu turno. Cambia el `width`. Prueba `80%`, luego `40%` y vuelve a `60%`. Observa cómo cambia el ancho de la caja y cómo sigue centrada gracias a `margin: auto;`."
>
> **Bloque F: Errores comunes (45-60 segundos)**
> - **Visual:** Se muestra `margin: auto;` sin `width` definido y la caja no se centra.
> - **Voz en off (Audio):** "Si escribes `margin: auto;` y no ves que la caja se centre, revisa si tiene un ancho definido. Sin un ancho, `margin: auto` no tiene efecto."
>
> **Bloque G: Cierre (30-45 segundos)**
> - **Visual:** Diagrama del modelo de caja: contenido → padding → border → margin.
> - **Voz en off (Audio):** "Hoy aprendiste el modelo de caja: contenido, padding (espacio interior), border (borde) y margin (espacio exterior). También viste cómo centrar bloques con `margin: auto`. En la siguiente lección aplicaremos todo esto en un proyecto final."

## 4. Sugerencias Multimedia

- **Anotaciones en Pantalla:** Mostrar el diagrama del modelo de caja con las 4 capas etiquetadas.
- **Resaltado de Sintaxis:** Resaltar `border`, `padding`, `margin` y `width` con colores diferentes.
- **Animación:** Animar el padding creciendo desde el borde hacia el contenido, y el margin alejando la caja de sus vecinas.
