# Lección 1: ¿Qué es el desarrollo web?

_(Contenido para los instructores)_

## 1. Estructura de Carpetas (GitHub)

```text
/starter-files/lesson-01        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-01   # El código completo de la lección
├── index.html
└── styles.css
```

## 2. Ficha Técnica

- **Duración estimada:** 5 minutos.
- **Objetivo de aprendizaje:** Comprender el concepto básico de desarrollo web y diferenciar claramente el rol de HTML (estructura) y CSS (estilos), utilizando CodePen.

## 3. Guion de Video (8 minutos)

> **[Escena 1: Introducción]**
> - **Visual:** Pantalla de bienvenida con el texto en pantalla: "¡Crea tu propia web en minutos!"
> - **Voz en off (Audio):** "¡Hola! ¿Alguna vez te has preguntado cómo se construyen las páginas web que visitas todos los días? Hoy vas a descubrirlo y, lo mejor de todo, ¡escribirás tu propio código en los próximos 5 minutos! No necesitas instalar ninguna aplicación, todo lo haremos desde el navegador."
>
> **Bloque A: ¿Dónde vemos desarrollo web todos los días? (45-60 segundos)**
> - **Visual:** Collage rápido de páginas web: una página educativa, una tienda en línea, una noticia y una plataforma de videos. Evitar mostrar marcas si no es necesario.
> - **Voz en off (Audio):** "Antes de escribir código, pensemos en algo muy simple: casi todo lo que usamos en internet vive dentro de una página o aplicación web. Cuando revisas una tarea, ves un video, lees una noticia o compras algo en línea, estás usando tecnologías web. Por eso aprender HTML y CSS es como aprender el alfabeto básico de internet. No necesitas saberlo todo desde el primer día; solo necesitas entender cómo se construye una página paso a paso."
>
> **[Escena 2: La Analogía del Edificio]**
> - **Visual:** Animación gráfica o dibujo en pantalla. Aparece el esqueleto de una casa de ladrillos, luego se pinta y decora.
> - **Voz en off (Audio):** "Imagina que una página web es como una casa. El **HTML** son los ladrillos, las paredes y el techo. Es el esqueleto que le da estructura a nuestra información. Por otro lado, el **CSS** es la pintura, los muebles y la decoración. Es lo que hace que nuestra casa (o página web) se vea increíble."
>
> **Bloque B: Separando contenido y apariencia (60-75 segundos)**
> - **Visual:** La casa se divide en dos capas: estructura y apariencia. Luego se muestra una página sencilla con texto negro sobre fondo blanco, y después la misma página con colores.
> - **Voz en off (Audio):** "Lo importante es separar dos ideas. Primero está el contenido: qué texto aparece, qué título se muestra o qué información queremos comunicar. Esa parte corresponde a HTML. Luego está la presentación: el color del título, el tamaño del texto, los espacios o si algo aparece centrado. Esa parte corresponde a CSS. Separar contenido y estilo hace que una página sea más fácil de entender, corregir y mejorar. Si queremos cambiar el mensaje, tocamos HTML. Si queremos cambiar cómo se ve, tocamos CSS."
>
> **[Escena 3: Entorno de Trabajo (CodePen)]**
> - **Visual:** Grabación de pantalla mostrando la interfaz de CodePen. Resaltar en rojo los paneles de HTML, CSS y Resultado.
> - **Voz en off (Audio):** "Para empezar, usaremos una plataforma increíble llamada CodePen. Es una herramienta 100% online donde escribimos código y vemos el resultado al instante. HTML nos dice qué contenido debe aparecer, CSS nos dice cómo se ve y el navegador combina ambos para mostrarnos la página en el área de Resultado."
>
> **[Escena 4: Manos a la Obra]**
> - **Visual:** Escribiendo en el panel de HTML. Un zoom suave al texto.
>   ```html
>   <h1>Hola Mundo</h1>
>   <p>Mi primera página</p>
>   ```
> - **Voz en off (Audio):** "Vamos a escribir nuestro primer código HTML. Piensa en esto como decirle al navegador qué contenido debe colocar en la página. No hace falta memorizar nada todavía; solo observa cómo el texto aparece en el resultado de inmediato. Pero se ve un poco aburrido, ¿verdad? Vamos a darle vida."
>
> **[Escena 5: Agregando Estilos]**
> - **Visual:** Escribiendo en el panel de CSS. Resaltar la propiedad color.
> - **Voz en off (Audio):** "Ahora vamos al panel de CSS. Aquí no cambiamos el contenido, solo la apariencia. Escribimos la regla dentro de las llaves del selector `h1`, así: `h1 { color: blue; }`. El navegador toma esa instrucción, la aplica al título y lo pinta de azul. El texto sigue siendo el mismo, pero ahora se ve diferente. Con solo dos líneas de código, ya has empezado tu viaje en el desarrollo web."
>
> **Bloque E: Ahora es tu turno: cambia el título y el párrafo (60-75 segundos)**
> - **Visual:** Pantalla con texto: "Ahora es tu turno: personaliza tu mini página". Puede aparecer un temporizador breve de 15 a 20 segundos.
> - **Voz en off (Audio):** "Ahora es tu turno. Cambia el texto Hola Mundo por un título propio, como Bienvenido a mi sitio o Mi página personal. Después cambia el párrafo Mi primera página por una frase corta, por ejemplo: Estoy aprendiendo HTML y CSS o Aquí compartiré mis intereses. No borres las etiquetas <h1>, </h1>, <p> ni </p>. Cambia solo el texto que está en medio. Cuando termines, mira el panel de Resultado y verifica que tu página ya tenga tu propio mensaje."
>
> **Bloque F: Error común de principiantes en HTML y CSS (75-90 segundos)**
> - **Visual:** Se borra accidentalmente </h1> o </p>, luego se muestra una regla CSS sin llave o sin punto y coma. Después se corrige.
> - **Voz en off (Audio):** "Un error común al empezar es borrar una parte del código sin darse cuenta. Por ejemplo, si eliminas el cierre </h1> o </p>, el navegador puede intentar adivinar qué querías hacer, pero el código queda incompleto. En CSS también hay detalles importantes: las reglas usan llaves { }, y las instrucciones suelen terminar con punto y coma ;. Cuando algo no funcione, revisa con calma: ¿cada etiqueta se abrió y se cerró?, ¿la regla de CSS tiene llaves?, ¿la línea termina con punto y coma? Programar también consiste en revisar pequeños detalles."
>
> **Bloque G: Cierre ampliado y conexión con la siguiente lección (45-60 segundos)**
> - **Visual:** Resumen en tres tarjetas: HTML = contenido, CSS = estilo, navegador = resultado.
> - **Voz en off (Audio):** "Antes de terminar, recuerda estas tres ideas: HTML crea el contenido, CSS cambia la apariencia y el navegador une todo para mostrar la página. Hoy no buscamos memorizar muchas etiquetas, sino entender el mapa general del desarrollo web. Ya escribiste un título, viste como aparece en pantalla y cambiaste su estilo con CSS. En la siguiente lección construiremos una estructura más completa, como si pasáramos de una sola pared al plano completo de una casa."

## 4. Sugerencias Multimedia

- **Anotaciones en Pantalla:** 
  - Mostrar la analogía visual de la casa: estructura de ladrillo/concreto (HTML) vs. diseño pintado y decorado (CSS).
  - Resaltar la división del entorno de CodePen: áreas de edición de HTML, CSS y la vista previa del Resultado.
- **Resaltado de Sintaxis:** 
  - Resaltar en rojo las etiquetas `<h1>...</h1>` y `<p>...</p>` en HTML.
  - Resaltar los elementos clave de la sintaxis CSS: selector (`h1`), llaves `{...}`, propiedad (`color`), valor (`blue`) y punto y coma `;`.
- **Transiciones:** 
  - Transición suave con zoom para enfocar el editor de código al pasar de la analogía a la escritura práctica.
  - Mostrar un temporizador animado en pantalla de 15-20 segundos durante el bloque del reto práctico.
