# Guiones de Video {-}

A continuación se presentan los guiones completos utilizados para la grabación de cada lección del curso. Cada guion incluye la estructura de carpetas del repositorio, el guion detallado con marcas de tiempo y las sugerencias multimedia para la edición del video.

## Lección 1: ¿Qué es el Desarrollo Web? {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-01        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-01   # El código completo de la lección
├── index.html
└── styles.css
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción**

¡Hola! ¿Alguna vez te has preguntado cómo se construyen las páginas web que visitas todos los días? Hoy vas a descubrirlo y, lo mejor de todo, ¡escribirás tu propio código en los próximos 5 minutos! No necesitas instalar ninguna aplicación, todo lo haremos desde el navegador.

**(1:00 - 2:00) ¿Dónde vemos desarrollo web todos los días?**

Antes de escribir código, pensemos en algo muy simple: casi todo lo que usamos en internet vive dentro de una página o aplicación web. Cuando revisas una tarea, ves un video, lees una noticia o compras algo en línea, estás usando tecnologías web. Por eso aprender HTML y CSS es como aprender el alfabeto básico de internet.

**(2:00 - 3:00) La Analogía del Edificio**

Imagina que una página web es como una casa. El **HTML** son los ladrillos, las paredes y el techo. Es el esqueleto que le da estructura a nuestra información. Por otro lado, el **CSS** es la pintura, los muebles y la decoración. Es lo que hace que nuestra casa (o página web) se vea increíble.

**(3:00 - 4:00) Separando contenido y apariencia**

Lo importante es separar dos ideas. Primero está el contenido: qué texto aparece, qué título se muestra. Esa parte corresponde a HTML. Luego está la presentación: el color del título, el tamaño del texto. Esa parte corresponde a CSS. Separar contenido y estilo hace que una página sea más fácil de entender, corregir y mejorar.

**(4:00 - 5:00) Entorno de Trabajo (CodePen)**

Para empezar, usaremos una plataforma increíble llamada CodePen. Es una herramienta 100% online donde escribimos código y vemos el resultado al instante.

**(5:00 - 6:00) Manos a la Obra**

Vamos a escribir nuestro primer código HTML: `<h1>Hola Mundo</h1>` y `<p>Mi primera página</p>`. Luego en el panel de CSS escribimos `h1 { color: blue; }`. El navegador toma esa instrucción y pinta el título de azul.

**(6:00 - 7:00) Ahora es tu turno**

Cambia el texto "Hola Mundo" por un título propio, como "Bienvenido a mi sitio". Después cambia el párrafo por una frase corta. No borres las etiquetas. Cambia solo el texto que está en medio.

**(7:00 - 8:00) Cierre y Errores Comunes**

Un error común es borrar una parte del código sin darse cuenta. En CSS: ¿las reglas tienen llaves? ¿Las instrucciones terminan con punto y coma? Programar también consiste en revisar pequeños detalles.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la analogía visual de la casa: estructura (HTML) vs. diseño (CSS).
- **Resaltado de Sintaxis:** Resaltar etiquetas `<h1>`, `<p>` en HTML y selector, llaves, propiedad, valor en CSS.
- **Transiciones:** Transición suave con zoom para enfocar el editor de código.

---

## Lección 2: El Esqueleto de tu Página {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-02        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-02   # El código completo de la lección
├── index.html
└── styles.css
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción al Esqueleto Humano**

¡Hola de nuevo! En la lección anterior vimos cómo mostrar contenido y darle estilo. Ahora vamos a construir la base de la página para que el navegador entienda dónde empieza todo.

**(1:00 - 2:30) La Etiqueta Principal**

Todo empieza con la etiqueta `<html>`. Esta etiqueta envuelve a toda la página. Dentro podemos añadir un atributo como `lang="es"` para decirle al navegador que el contenido está en español.

**(2:30 - 3:30) El Documento HTML Completo**

La línea `<!DOCTYPE html>` le indica al navegador que estamos usando HTML moderno. La estructura completa es: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`. En CodePen no siempre necesitamos escribir toda la estructura, pero es importante conocerla.

**(3:30 - 4:30) La Cabeza (El cerebro de la página)**

Dentro de `<html>` tenemos la etiqueta `<head>`. Aquí colocamos información para el navegador que no se ve en la página, como el texto de la pestaña con `<title>`.

**(4:30 - 5:30) El Cuerpo (Lo que todos ven)**

Luego viene `<body>`, el cuerpo. Aquí colocamos todo lo que el visitante vea: títulos, párrafos, imágenes y más.

**(5:30 - 6:30) Anidamiento de Etiquetas**

Las etiquetas se abren y se cierran con `/`. La indentación nos ayuda a ver qué va dentro de qué. Es como una mochila: dentro puedes tener una cartuchera, y dentro lápices.

**(6:30 - 7:15) Ahora es tu turno**

Observa un código desordenado y acomódalo visualmente usando espacios. Recuerda: `<head>` y `<body>` están dentro de `<html>`, y los elementos internos también deben ir indentados.

**(7:15 - 8:00) Cierre y Errores Comunes**

Uno de los errores más normales es olvidar cerrar una etiqueta. HTML puede ser flexible, pero no conviene depender de eso. La buena práctica es cerrar cada sección.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la analogía del esqueleto humano: cabeza (`<head>`) vs. cuerpo (`<body>`).
- **Resaltado de Sintaxis:** Resaltar etiquetas `<html>`, `<head>`, `<body>`, `<title>` y el atributo `lang="es"`.
- **Transiciones:** Animación de indentación para explicar el anidamiento de etiquetas.

---

## Lección 3: Organizando la Información {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-03        # Carpeta con el codigo base para la clase
└── index.html
/completed-examples/lesson-03   # El código completo de la lección
└── index.html
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción**

¡Hola! Imagina leer un libro que no tiene títulos, capítulos ni separación entre párrafos. Sería muy difícil de entender, ¿verdad? Lo mismo pasa en las páginas web. Hoy aprenderemos a organizar nuestra información.

**(1:00 - 2:00) ¿Cómo leemos una página?**

Si todo aparece en un solo bloque gigante, el visitante se cansa rápido. Cuando usamos títulos, párrafos y listas, la información se vuelve más fácil de explorar. Organizar no significa decorar; significa darle estructura al contenido.

**(2:00 - 3:30) Los Encabezados (Jerarquía)**

Para crear títulos usamos `<h1>` hasta `<h6>`. El `<h1>` es el título principal, solo debe haber uno por página. Los `<h2>` y `<h3>` son subtítulos. Lo importante es elegir el encabezado por la importancia del contenido, no por el tamaño.

**(3:30 - 4:30) Los Párrafos**

El párrafo `<p>` sirve para desarrollar una idea. Si el encabezado dice "Mis Películas Favoritas", el párrafo explica por qué te gusta ese tema. Los encabezados guían; los párrafos cuentan.

**(4:30 - 6:00) Las Listas (Ordenadas y Desordenadas)**

Si el orden no importa usamos `<ul>` (viñetas). Si el orden es clave usamos `<ol>` (números). Cada elemento se escribe con `<li>`. La lista es la caja grande, y cada elemento va dentro de su propia etiqueta `<li>`.

**(6:00 - 7:00) Ahora es tu turno**

Escribe tres elementos dentro de tu lista. Pueden ser tres películas, tres videojuegos o tres metas. Cuando termines, revisa si cada elemento tiene apertura y cierre.

**(7:00 - 8:00) Cierre y Errores Comunes**

Un error común es escribir `<li>` fuera de una lista. Los `<li>` deben estar dentro de `<ul>` o `<ol>`. Si es una explicación larga, usa `<p>`, no un encabezado.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la jerarquía de encabezados como una pirámide visual.
- **Resaltado de Sintaxis:** Resaltar etiquetas `<h1>`, `<h2>`, `<p>`, `<ul>`, `<ol>`, `<li>` con colores diferentes.
- **Transiciones:** Transición animada de página desorganizada a organizada.

---

## Lección 4: Multimedia y Navegación {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-04        # Carpeta con el codigo base para la clase
└── index.html
/completed-examples/lesson-04   # El código completo de la lección
└── index.html
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción**

¡Hola! Hasta ahora nuestra página tiene mucha información valiosa, pero admitámoslo, ¡el texto solo puede ser un poco aburrido! Es hora de añadir imágenes y enlaces.

**(1:00 - 2:00) Elegir imágenes con propósito**

Antes de insertar cualquier imagen, pensemos en su propósito. Una imagen debe ayudar a entender mejor el contenido. En una buena página web, las imágenes no son solo decoración: también comunican.

**(2:00 - 3:30) Insertando la primera imagen**

Para agregar una foto usamos `<img>`. Esta etiqueta no necesita cerrarse. Lo que necesita es el atributo `src` (fuente) con la dirección de la imagen. El `src` puede recibir una URL de internet o una ruta de archivo.

**(3:30 - 4:30) El atributo de accesibilidad (alt)**

Si la imagen no carga, o si una persona con discapacidad visual visita nuestra página, usamos `alt` para describir qué hay en la foto. Un buen `alt` describe lo importante, no solo dice "imagen".

**(4:30 - 6:00) Viajando por internet (Enlaces)**

Usamos `<a>` (ancla) con el atributo `href` para crear enlaces. El `href` es el destino, y el texto entre `<a>` y `</a>` es lo que se muestra en pantalla. Los enlaces deben estar relacionados con el contenido cercano.

**(6:00 - 7:00) Ahora es tu turno**

Elige un tema, busca una imagen relacionada y crea `<img>` con `src` y `alt`. Después agrega un enlace con `<a>` hacia una página relacionada. Revisa que la imagen cargue y que el enlace funcione.

**(7:00 - 8:00) Cierre y Errores Comunes**

Evita usar "clic aquí" como texto de enlace. Es mejor que el texto explique el destino, como "visita la página de la NASA". El enlace debe ayudar a ampliar la información.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la anatomía de `<img>` y `<a>` con flechas señalando cada parte.
- **Resaltado de Sintaxis:** Resaltar `src`, `alt` y `href` con colores diferentes.
- **Transiciones:** Transición de página solo texto a página con imágenes y enlaces.

---

## Lección 5: Conoce a CSS {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-05        # Archivo base listo para escribir el código en vivo
├── index.html
└── styles.css
/completed-examples/lesson-05   # El código final con las reglas CSS aplicadas correctamente
├── index.html
└── styles.css
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción: Es hora de decorar**

Hasta ahora hemos construido un esqueleto usando HTML. Sin embargo, no tiene mucho estilo. ¡Es hora de pintar y decorar! Hoy conocemos oficialmente a CSS (*Hojas de Estilo en Cascada*).

**(1:00 - 2:30) La Regla CSS y el Selector**

A diferencia de HTML, en CSS no usamos etiquetas. Usamos 'reglas'. El **selector** indica a quién queremos dar estilo. Podemos usar el nombre de una etiqueta, una clase (`.destacado`) o un id (`#principal`).

**(2:30 - 3:30) Las Llaves y Propiedades**

Una vez que llamamos al selector, abrimos llaves `{}`. Todo lo que escribamos dentro será la lista de instrucciones de diseño. Las instrucciones se dividen en propiedad y valor, separados por dos puntos y terminados con punto y coma.

**(3:30 - 5:00) Propiedades y Valores**

Le decimos `background-color: lightblue;` para pintar el fondo. Para el título usamos `color: darkblue;`. Los colores aceptan nombres en inglés (`red`, `blue`) o códigos hexadecimales (`#fce4ec`).

**(5:00 - 6:00) Contraste y legibilidad**

No todos los colores funcionan bien juntos. Si el fondo es claro y el texto también, será difícil leer. Un buen diseño no solo se ve bonito: también se entiende. Revisa si puedes leer el texto sin esfuerzo.

**(6:00 - 7:00) Ahora es tu turno**

Prueba dos combinaciones de colores. Cambia el fondo del `body` y el color del `h1`. Observa qué combinaciones se ven bien y cuáles no.

**(7:00 - 8:00) Cierre y Formas de Escribir CSS**

Cuando CSS no funciona, revisa la puntuación. Existen varias formas de escribir CSS: panel separado (la más ordenada), dentro de `<style>` en el `<head>`, o con el atributo `style` (no recomendado para mucho código).

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la anatomía de una regla CSS: selector, llaves, propiedad, valor, punto y coma.
- **Resaltado de Sintaxis:** Resaltar selectores, propiedades y valores con colores diferentes.
- **Transiciones:** Transición de página sin estilo a página con colores aplicados.

---

## Lección 6: Tipografía y Estilo {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-06        # Archivo base listo para escribir el código en vivo
├── index.html
└── styles.css
/completed-examples/lesson-06   # El código final con las reglas CSS aplicadas correctamente
├── index.html
└── styles.css
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción: El poder de las letras**

¡Hola de nuevo! Imagina que lees una solicitud formal escrita con letras de cómic; nadie te tomaría en serio. La letra, o 'tipografía', comunica emociones. Hoy le pondremos personalidad a nuestra página.

**(1:00 - 2:30) Cambiando la Fuente (font-family)**

Para cambiar el tipo de letra usamos `font-family`. Escribimos `font-family: Verdana, sans-serif;` para dar una primera opción y una de respaldo. Las fuentes sans-serif se leen fácilmente en pantalla.

**(2:30 - 3:30) Traer fuentes de internet**

Hay una biblioteca gratuita llamada Google Fonts. Si encuentras una fuente genial como 'Roboto' o 'Pacifico', puedes importarla a tu proyecto. Por ahora usaremos fuentes que ya vienen en todos los navegadores.

**(3:30 - 4:30) Tamaños y Jerarquía visual**

Lo más importante debe ser lo más grande. Usamos `font-size` para darle al `h1` un tamaño de 40px y al párrafo 18px. Esto crea una jerarquía visual que guía los ojos del visitante.

**(4:30 - 5:30) Alineación y lectura**

Con `text-align: center;` centramos el título. Pero no siempre conviene centrar textos largos porque puede cansar. Para párrafos largos, la alineación izquierda suele ser más cómoda.

**(5:30 - 6:30) Ahora es tu turno**

Cambia el tamaño del párrafo. Prueba `18px`, luego `20px` y después `24px`. Pregúntate: ¿cuál se lee mejor? No hay una única respuesta perfecta.

**(6:30 - 7:30) Errores comunes**

En CSS, las propiedades usan guiones: `font-family`, no `font family`. Si una propiedad está mal escrita, el navegador la ignora. Cuando algo no cambie, revisa primero el nombre exacto de la propiedad.

**(7:30 - 8:00) Cierre**

Hoy aprendiste que el texto también se diseña. La fuente define personalidad, el tamaño ayuda a leer y la alineación guía la atención.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar la diferencia entre fuentes serif y sans-serif con ejemplos visuales.
- **Resaltado de Sintaxis:** Resaltar `font-family`, `font-size` y `text-align` con colores diferentes.
- **Transiciones:** Transición de texto con fuente por defecto a texto con fuentes personalizadas.

---

## Lección 7: Espacios y Bordes {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-07        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-07   # El código completo de la lección
├── index.html
└── styles.css
```

### Guion de Video (8 minutos) {-}

**(0:00 - 1:00) Introducción**

Nuestra aplicación va tomando forma, pero tiene un problema: todo está pegado a los bordes. ¡Nuestros textos necesitan respirar! Hoy aprenderemos a darle espacio a las cosas y a ponerles marcos.

**(1:00 - 2:00) ¿Qué es un div?**

Un `<div>` es como una caja o contenedor que nos permite agrupar varios elementos. Gracias a eso, podemos aplicar estilos a toda la caja completa en lugar de mover o decorar cada elemento por separado.

**(2:00 - 3:30) La Teoría de las Cajas**

En la web, todo es una caja invisible. Para ver estas cajas, ponemos un borde con `border: 2px solid black;`. El `2px` es el grosor, `solid` el tipo de línea, y `black` el color. Para darle espacio interior usamos `padding: 20px;`.

**(3:30 - 4:30) Margen (El Espacio Exterior)**

El `margin` empuja hacia afuera. Si al párrafo le ponemos `margin-top: 30px;`, le estamos diciendo que se aleje 30 píxeles para arriba. Mientras padding empuja hacia adentro, margin empuja hacia afuera.

**(4:30 - 5:30) El Truco Mágico: Centrar Bloques**

Para centrar una caja en medio de la pantalla, primero le damos un ancho fijo con `width: 50%;`. Luego aplicamos `margin: auto;`. Esto le dice al navegador que reparta el espacio sobrante equitativamente a los lados.

**(5:30 - 6:30) Ahora es tu turno**

Cambia el `width`. Prueba `80%`, luego `40%` y vuelve a `60%`. Observa cómo cambia el ancho y cómo sigue centrada gracias a `margin: auto;`.

**(6:30 - 7:30) Errores comunes**

Si escribes `margin: auto;` y no ves que la caja se centre, revisa si tiene un ancho definido. Sin un ancho, `margin: auto` no tiene efecto. También revisa que estés aplicando la regla al elemento correcto.

**(7:30 - 8:00) Cierre**

Hoy aprendiste el modelo de caja: contenido, padding (interior), border (borde) y margin (exterior). También viste cómo centrar bloques con `margin: auto`.

### Sugerencias Multimedia {-}

- **Anotaciones en Pantalla:** Mostrar el diagrama del modelo de caja con las 4 capas etiquetadas.
- **Resaltado de Sintaxis:** Resaltar `border`, `padding`, `margin` y `width` con colores diferentes.
- **Animación:** Animar el padding creciendo desde el borde hacia el contenido.

---

## Lección 8: Proyecto Final y Próximos Pasos {-}

### Estructura de Carpetas (GitHub) {-}

```text
/starter-files/lesson-08        # Plantilla base con index.html y styles.css vacíos
├── index.html
└── styles.css
/completed-examples/lesson-08   # El proyecto final: Perfil Personal completo
├── index.html
└── styles.css
```

### Guion de Video (10 minutos) {-}

**(0:00 - 1:00) El Gran Final**

¡Felicidades! Has llegado a la última lección. Has aprendido el esqueleto (HTML) y la pintura (CSS), cómo organizar información y dar espacio al diseño. Ahora crearemos tu primera aplicación web completa: un Perfil Personal en línea.

**(1:00 - 2:00) Presentación del producto final**

Nuestra página tendrá una tarjeta de perfil personal. En la parte superior colocaremos una imagen o avatar, luego un título con el nombre, un párrafo breve de presentación y una sección de enlaces.

**(2:00 - 3:30) La caja principal del perfil en HTML**

Creamos un `<div>` con la clase `tarjeta-perfil` para agrupar todo. Dentro colocamos la imagen con `<img>`, el nombre con `<h1>`, una biografía con `<p>` y enlaces con `<ul>` y `<li>`.

**(3:30 - 5:00) Conectando HTML y CSS**

En HTML escribimos `class="tarjeta-perfil"`, y en CSS usamos `.tarjeta-perfil`. Esta relación es clave: HTML crea los elementos y CSS decide cómo se ven.

**(5:00 - 7:00) Dando forma visual a la tarjeta con CSS**

Con `background-color: white;` hacemos que destaque. Con `width: 300px;` controlamos el ancho. Con `margin: auto;` la centramos. `padding: 30px;` agrega espacio interior. `border-radius: 15px;` redondea las esquinas. `box-shadow` agrega una sombra suave.

**(7:00 - 8:30) Estilo de imagen y enlaces**

La imagen se convierte en círculo con `border-radius: 50%;`. La lista se limpia con `list-style: none;`. Los enlaces se personalizan con `a { color: #c2185b; }`.

**(8:30 - 9:15) Revisión de Errores Comunes**

Verifica: ¿el div tiene la clase? ¿La clase existe en CSS? ¿La imagen tiene `src` y `alt`? ¿Los enlaces tienen `href`? ¿Las etiquetas están cerradas? ¿CSS tiene puntos y comas?

**(9:15 - 10:00) Personalización y Próximos Pasos**

Personaliza tu perfil: cambia nombre, descripción, enlaces, colores e imagen. Este proyecto resume todo lo aprendido: estructura HTML, imágenes, enlaces, colores, tipografía, espacios y bordes. A partir de aquí puedes seguir con diseño adaptable, formularios y JavaScript.

### Sugerencias Multimedia {-}

- **Diploma Digital Animado:** Mostrar un diploma girando durante la introducción con efecto de confeti.
- **Preview Anotado:** Mostrar la tarjeta terminada con flechas señalando cada elemento antes de construirla.
- **Resaltado Progresivo:** Conforme se menciona cada etiqueta, resaltarla con un color diferente.
- **Animación Propiedad por Propiedad:** Agregar cada línea de CSS una a una y mostrar cómo cambia la tarjeta.
- **Checklist Animado:** Los puntos del checklist aparecen uno a uno con palomita verde.
