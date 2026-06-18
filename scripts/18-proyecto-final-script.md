# Lección 8: Proyecto Final y Próximos Pasos

_(Contenido para los instructores)_

## 1. Estructura de Carpetas (GitHub)

```text
/lesson-8
├── /starter          # Plantilla base con index.html y style.css vacíos
│   ├── index.html
│   └── style.css
└── /completed        # El proyecto final: Perfil Personal completo
    ├── index.html
    └── style.css
```

## 2. Ficha Técnica

- **Duración estimada:** 10 minutos.
- **Objetivo de aprendizaje:** Integrar todos los conceptos aprendidos (HTML semántico, enlaces, imágenes, y CSS con Box Model y tipografía) para construir una "Página de Perfil Personal" en Replit y revisar errores sintácticos comunes.

## 3. Guion de Video

**[Escena 1: El Gran Final]**
- **Visual:** El instructor aplaude frente a la cámara. Aparece en pantalla un diploma digital girando.
- **Instructor (Audio):** "¡Felicidades! Has llegado a la última lección. Has aprendido el esqueleto (HTML) y la pintura (CSS), cómo organizar información y dar espacio al diseño. Ahora, tomaremos todo eso para cumplir nuestro requisito final: crear tu primera aplicación web completa, un Perfil Personal en línea."

**Bloque A: Presentación clara del producto final (60 segundos)**
- **Visual:** Vista previa de la tarjeta de perfil terminada. Se señalan sus partes: imagen, nombre, descripción y enlaces.
- **Instructor (Audio):** "Antes de empezar, veamos qué construiremos. Nuestra página tendrá una tarjeta de perfil personal. En la parte superior colocaremos una imagen o avatar. Luego agregaremos un título con el nombre, un párrafo breve de presentación y una sección de enlaces. La idea no es que todos hagan exactamente la misma página, sino que cada uno pueda personalizarla con su nombre, sus gustos, sus colores y sus propios enlaces."

**[Escena 2: Uniendo Piezas]**
- **Visual:** Se muestra rápidamente cómo se estructura un div, una imagen de perfil redonda y enlaces sociales.
- **Instructor (Audio):** "Para tu proyecto final, crearás una tarjeta centrada usando nuestro truco `margin: auto`. Le pondrás tu nombre con un `<h1>`, una foto tuya o de tu avatar con la etiqueta `<img>`, una breve biografía en un párrafo `<p>` y, al final, una lista desordenada `<ul>` con enlaces `<a>` a tus redes o hobbies favoritos."

**Bloque B: La caja principal del perfil en HTML (75 segundos)**
- **Visual:** En CodePen se resalta `<div class="tarjeta-perfil">` y luego se dibuja un rectángulo alrededor de todo el contenido.
- **Instructor (Audio):** "Primero necesitamos una caja principal para guardar todo el perfil. Para eso usamos un `div` con la clase `tarjeta-perfil`. El `div` no muestra algo especial por sí solo, pero nos permite agrupar varios elementos. Dentro de esta caja colocaremos la imagen, el nombre, la descripción y los enlaces. La clase `tarjeta-perfil` será importante porque después, desde CSS, podremos darle forma a toda esta caja."

**Bloque C: Agregando la imagen del perfil con `<img>` (75 segundos)**
- **Visual:** En CodePen se escribe o resalta la etiqueta `<img src="..." alt="...">`. Luego aparece la imagen en el resultado.
- **Instructor (Audio):** "Ahora agregamos la imagen del perfil usando la etiqueta `<img>`. Esta etiqueta necesita el atributo `src`, donde colocamos la dirección de la imagen. También usamos `alt`, que sirve para describir la imagen si no carga o si una persona usa un lector de pantalla. En este ejemplo usamos una imagen de avatar, pero tú podrías usar una foto propia o una imagen libre."

**Bloque D: Agregando nombre y descripción con `<h1>` y `<p>` (60 segundos)**
- **Visual:** Se resaltan las líneas `<h1>Ana Pérez</h1>` y `<p>...</p>`. En el resultado se marca el nombre y la descripción.
- **Instructor (Audio):** "Después de la imagen colocamos el nombre con un `<h1>`, porque será el título principal de nuestra tarjeta. Debajo escribimos una breve presentación dentro de un párrafo `<p>`. Aquí puedes contar algo sencillo sobre ti: tus gustos, tus intereses o lo que estás aprendiendo. Con esto, la tarjeta ya empieza a tener identidad."

**Bloque E: Creando la sección de enlaces con lista y anclas (90 segundos)**
- **Visual:** Se resaltan `<h2>Mis Enlaces</h2>`, `<ul>`, `<li>` y `<a href="...">`. Luego se muestran los enlaces en el resultado.
- **Instructor (Audio):** "Ahora agregamos una sección para los enlaces. Primero usamos un `<h2>` con el texto 'Mis Enlaces'. Luego creamos una lista desordenada con `<ul>`. Dentro de la lista, cada elemento va con `<li>`. Y dentro de cada elemento colocamos un enlace usando `<a>`. El atributo `href` indica a qué página irá el visitante cuando haga clic. Por ejemplo, podemos enlazar GitHub, un blog o una página que nos guste."

**Bloque F: Conectando HTML y CSS con la clase tarjeta-perfil (60 segundos)**
- **Visual:** Pantalla dividida: a la izquierda el HTML con `class="tarjeta-perfil"` resaltado y a la derecha el CSS con `.tarjeta-perfil` resaltado.
- **Instructor (Audio):** "Observa esta conexión: en HTML escribimos `class="tarjeta-perfil"`, y en CSS usamos `.tarjeta-perfil` con un punto al inicio. Eso significa que todos los estilos dentro de esa regla se aplicarán a nuestra caja principal. Esta relación entre HTML y CSS es clave: HTML crea los elementos y CSS decide cómo se ven."

**Bloque G: Dando forma visual a la tarjeta con CSS (90 segundos)**
- **Visual:** Se escribe la regla `.tarjeta-perfil` paso a paso: fondo blanco, ancho, centrado, padding, bordes redondeados y sombra.
- **Instructor (Audio):** "Ahora sí vamos a darle diseño a la tarjeta. Con `background-color: white;` hacemos que destaque sobre el fondo. Con `width: 300px;` controlamos su ancho. Con `margin: auto;` la centramos. Luego `padding: 30px;` agrega espacio interior para que el contenido no toque los bordes. `border-radius: 15px;` redondea las esquinas, `text-align: center;` centra el contenido, y `box-shadow` agrega una sombra suave para que parezca una tarjeta real."

**Bloque H: Dando estilo a la imagen y a los enlaces (90 segundos)**
- **Visual:** Se muestra la imagen cuadrada y luego redonda. Después se muestra la lista con viñetas y luego limpia.
- **Instructor (Audio):** "También podemos mejorar partes específicas. En la imagen usamos `width` y `height` de `150px` para darle un tamaño fijo. Con `object-fit: cover;` evitamos que se deforme, y con `border-radius: 50%;` la convertimos en un círculo. Luego limpiamos la lista con `list-style: none;` y `padding: 0;`, para quitar las viñetas y el espacio extra. En cada `li` agregamos margen para separar los enlaces, y con `a { color: #c2185b; }` cambiamos el color de los enlaces."

**[Escena 3: Revisión de Errores Comunes (Checklist)]**
- **Visual:** Un rayo rojo golpea la pantalla, revelando una lista de chequeo de errores comunes. El instructor tiene una lupa.
- **Instructor (Audio):** "Antes de terminar, revisa esta lista. Primero, confirma que el `div` principal tenga la clase `tarjeta-perfil`. Segundo, revisa que esa misma clase exista en CSS como `.tarjeta-perfil`. Tercero, verifica que la imagen tenga `src` y `alt`. Cuarto, asegúrate de que los enlaces tengan `href`. Quinto, revisa que etiquetas como `<div>`, `<ul>`, `<li>` y `<a>` estén bien cerradas. Y sexto, en CSS confirma que no falten puntos y comas o llaves de cierre."

**Bloque J: Personalización responsable y próximos pasos (75 segundos)**
- **Visual:** Tres variaciones de la misma tarjeta con diferentes colores, nombres e imágenes. Luego aparece una ruta de aprendizaje: HTML → CSS → Diseño adaptable → JavaScript.
- **Instructor (Audio):** "Ahora puedes personalizar tu perfil. Cambia el nombre, la descripción, los enlaces, los colores y la imagen. Solo recuerda mantener la legibilidad: el texto debe poder leerse sin esfuerzo. También evita usar imágenes sin permiso en proyectos públicos; puedes usar un avatar propio o una imagen libre. Este proyecto final resume todo lo aprendido: estructura HTML, imágenes, enlaces, colores, tipografía, espacios y bordes. A partir de aquí puedes seguir practicando con diseño adaptable para celulares, formularios y más adelante JavaScript para crear páginas interactivas."

## 4. Sugerencias Multimedia

- **Diploma Digital Animado (Escena 1):** Mostrar un diploma girando o flotando en pantalla durante la introducción. Puede acompañarse con efecto de confeti o destellos digitales sobre la cámara del instructor.
- **Preview Anotado del Resultado Final (Bloque A):** Mostrar la tarjeta terminada con flechas o recuadros de colores señalando cada elemento (`<img>`, `<h1>`, `<p>`, sección de enlaces) antes de empezar a construirla, para que el estudiante sepa hacia dónde va.
- **Resaltado Progresivo de Código (Bloques B–E):** Conforme se menciona cada etiqueta, resaltarla con un color diferente tanto en el panel de código como en el resultado del navegador: un color para `<div>`, otro para `<img>`, otro para `<h1>` y `<p>`, otro para `<ul>`, `<li>` y `<a>`.
- **Pantalla Dividida con Flecha Animada (Bloque F):** Mostrar ambos archivos en split screen y dibujar una flecha animada que conecte `class="tarjeta-perfil"` en el HTML con `.tarjeta-perfil` en el CSS.
- **Animación Propiedad por Propiedad (Bloque G):** Agregar cada línea de `.tarjeta-perfil` una a la vez y mostrar cómo cambia la tarjeta en el resultado: primero el fondo, luego el ancho, luego el centrado, el padding, los bordes redondeados y finalmente la sombra.
- **Imagen Cuadrada → Redonda en Vivo (Bloque H):** Mostrar la imagen del perfil en su estado cuadrado, luego escribir `border-radius: 50%` en pantalla y ver la transformación circular en tiempo real.
- **Checklist Animado (Escena 3):** Los seis puntos del checklist aparecen uno a uno con una palomita verde conforme el instructor los menciona.
- **Ruta de Aprendizaje (Bloque J):** Mostrar un diagrama de camino o escalera con los siguientes pasos: HTML → CSS → Diseño adaptable → JavaScript, para motivar al estudiante a continuar aprendiendo.