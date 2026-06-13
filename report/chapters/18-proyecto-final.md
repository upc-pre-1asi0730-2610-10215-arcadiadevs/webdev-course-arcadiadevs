# Lección 8: Proyecto Final y Próximos Pasos

## Video de la Clase
*Enlace al video de YouTube:* [Añadir enlace aquí]

## Entorno de Práctica
Empieza a programar de inmediato (¡Sin instalar nada!):

- **[Abrir CodePen - Plantilla inicial precargada: https://codepen.io/pen](https://codepen.io/pen)**

![Interfaz de CodePen con los archivos index.html y style.css en paneles separados](../assets/class-8/codigo-inicial.png)

## Transcripción / Notas de la Clase
¡Felicidades, creadores! Has llegado a la última lección. Ya aprendiste el esqueleto de la web (HTML), su pintura (CSS), cómo organizar información con listas y tablas, y cómo dar espacio al diseño con el Box Model. Hoy tomamos todo eso y lo unimos para construir tu primera aplicación web completa: una **Página de Perfil Personal**.

![Conceptos del curso representados como piezas de un rompecabezas encajando](../assets/class-8/rompecabeza-ilustracion.png)

**¿Qué construiremos hoy?**
Antes de escribir una línea de código, veamos el resultado final. Nuestra página tendrá una tarjeta de perfil centrada en pantalla con cuatro elementos: una imagen o avatar en la parte superior, un título con el nombre, un párrafo breve de presentación y una sección de enlaces. La idea no es que todos hagan exactamente la misma página: cada uno podrá personalizarla con su nombre, sus gustos, sus colores y sus propios enlaces.

![Wireframe de una tarjeta de perfil con sus elementos HTML etiquetados: img, h1, p, ul y enlaces](../assets/class-8/wiframe-perfil.png)

**Mudándonos a Replit:**
Hasta ahora trabajamos en CodePen, donde HTML y CSS convivían en paneles del mismo editor. Para este proyecto final, daremos un paso profesional y usaremos Replit, una herramienta que nos permite tener nuestros archivos separados, tal como lo hacen los desarrolladores en el mundo real. Tendrás un `index.html` para tu estructura y un `style.css` para todo tu diseño. Conectarlos es sencillo: solo una línea en el `<head>` de tu HTML lo hace todo:
```html
<link rel="stylesheet" href="style.css">
```

**La Caja Principal: `<div class="tarjeta-perfil">`:**
Primero necesitamos una caja que agrupe todo el contenido del perfil. Para eso usamos un `<div>` con la clase `tarjeta-perfil`. El `<div>` no muestra algo especial por sí solo, pero nos permite agrupar varios elementos como si los metiéramos dentro de una caja invisible. La clase `tarjeta-perfil` será fundamental más adelante: desde CSS apuntaremos a ese nombre para darle forma, color y posición a toda la caja de una sola vez.

**La Imagen de Perfil con `<img>`:**
Dentro del `<div>`, agregamos la imagen del perfil con la etiqueta `<img>`. Esta etiqueta necesita dos atributos: `src`, donde colocamos la dirección de la imagen, y `alt`, que describe la imagen si no carga o si alguien usa un lector de pantalla. Puedes usar una foto propia, un avatar o una imagen de uso libre.

**Nombre y Descripción con `<h1>` y `<p>`:**
Después de la imagen colocamos el nombre con un `<h1>`, porque será el título principal de la tarjeta. Debajo escribimos una breve presentación dentro de un `<p>`. Aquí puedes contar algo sencillo sobre ti: tus gustos, tus intereses o lo que estás aprendiendo. Con esto, la tarjeta ya tiene identidad propia.

**La Sección de Enlaces con `<ul>`, `<li>` y `<a>`:**
Para los enlaces usamos una lista desordenada `<ul>`. Dentro, cada ítem va con `<li>`, y dentro de cada ítem colocamos un enlace con `<a>`. El atributo `href` indica a qué página irá el visitante al hacer clic: puede ser tu GitHub, tu blog o cualquier página que quieras compartir.

**Código de Inicio (Starter):**

*Abre esta plantilla en Replit y úsala como punto de partida:*

**HTML (index.html):**
```html
<html lang="es">
<head>
  <title>Mi Perfil Personal</title>
  <!-- Esto enlaza tu HTML con tu CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="tarjeta-perfil">
    <!-- Tu contenido va aquí: Imagen, nombre, bio, lista de enlaces -->

  </div>

</body>
</html>
```

**CSS (style.css):**
```css
body {
  font-family: "Arial", sans-serif;
  background-color: #fce4ec;
}

.tarjeta-perfil {
  background-color: white;
  width: 300px;
  /* ¡Usa el truco mágico para centrar! */

  /* Añade padding para dar espacio interior */

  /* Extra: vamos a darle bordes redondeados */
  border-radius: 15px;
}

/* Modifica el texto e imágenes como gustes */
```

**La Conexión entre HTML y CSS:**
Observa esta relación clave: en HTML escribimos `class="tarjeta-perfil"` y en CSS usamos `.tarjeta-perfil` con un punto al inicio. Ese punto le dice al navegador "aplica estos estilos a todo elemento que tenga esa clase". Si quieres cambiar cómo se ve la tarjeta, solo modificas ese bloque en CSS. HTML define qué existe; CSS decide cómo se ve.

[imagen de pantalla dividida: a la izquierda el HTML con class="tarjeta-perfil" resaltado, a la derecha el CSS con .tarjeta-perfil resaltado, con una flecha conectando ambos lados]

**Dando Forma Visual a la Tarjeta con CSS:**
Ahora aplicamos los estilos a `.tarjeta-perfil` paso a paso. Con `background-color: white;` hacemos que destaque sobre el fondo de color. Con `width: 300px;` controlamos su ancho. Con `margin: auto;` la centramos en la página. El `padding: 30px;` agrega espacio interior para que el contenido no toque los bordes. Con `border-radius: 15px;` redondeamos las esquinas, `text-align: center;` centra todo el contenido, y `box-shadow` añade una sombra suave que hace que parezca una tarjeta física real.

**Estilizando la Imagen y los Enlaces:**
También podemos mejorar partes específicas de la tarjeta. En la imagen usamos `width` y `height` de `150px` para darle un tamaño fijo, `object-fit: cover;` para evitar que se deforme, y `border-radius: 50%;` para convertirla en un círculo. Para la lista, `list-style: none;` y `padding: 0;` eliminan las viñetas y el espacio extra. En cada `<li>` agregamos margen para separar los enlaces, y con `a { color: #c2185b; }` cambiamos su color.

**Checklist: ¿Por qué no funciona mi código?**
Antes de pedir ayuda, revisa esta lista de seis puntos:

1. ¿El `<div>` principal tiene la clase `tarjeta-perfil`?
2. ¿En CSS esa misma clase aparece como `.tarjeta-perfil` (con punto al inicio)?
3. ¿La etiqueta `<img>` tiene los atributos `src` y `alt`?
4. ¿Los enlaces `<a>` tienen el atributo `href`?
5. ¿Están bien cerradas etiquetas como `<div>`, `<ul>`, `<li>` y `<a>`?
6. ¿En CSS no faltan puntos y comas `;` ni llaves de cierre `}`?

![Inspector revisando errores comunes en un fragmento de código](../assets/class-8/inspector.png)

**Personalización y Próximos Pasos:**
Ahora es tu turno. Cambia el nombre, la descripción, los enlaces, los colores y la imagen. Solo recuerda mantener la legibilidad: el texto siempre debe poder leerse sin esfuerzo. Usa avatares propios o imágenes de uso libre si tu proyecto será público. Este proyecto resume todo lo aprendido en el curso: estructura HTML, imágenes, enlaces, colores, tipografía, espacios y bordes. A partir de aquí puedes explorar diseño adaptable para celulares, formularios y, más adelante, JavaScript para crear páginas interactivas.

## Actividad Práctica:

**Reto Final (15-20 minutos): ¡Construye tu Perfil!**

1. Abre tu plantilla en Replit y ve al archivo `index.html`.
2. Dentro de `<div class="tarjeta-perfil">` agrega: una foto o avatar (`<img>`), tu nombre (`<h1>`), un párrafo sobre ti (`<p>`) y al menos dos enlaces (`<ul>` con `<a>`).
3. Ve a `style.css` y usa `margin: auto;` para centrar la tarjeta. Añade `padding: 30px;` para que el contenido respire.
4. Prueba diferentes valores de `background-color`, ajusta el `border-radius` y personaliza los colores a tu gusto.
5. Corre tu código, revisa el checklist si algo falla y ¡obsérvalo brillar! Tienes tu propia página web en línea.

## Recursos Complementarios del Proyecto

![Resultado final: la tarjeta de perfil terminada y centrada en el navegador](../assets/class-8/imagen-final.png)

**Código Final (Solution):**

**HTML (index.html):**
```html
<html lang="es">
<head>
  <title>Perfil de Estudiante</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="tarjeta-perfil">
    <img src="https://img.freepik.com/fotos-premium/personaje-dibujos-animados-3d-mujer-joven-recibiendo-cumplido-emociones-alegria-verguenza-sonriendo-chica-morena-linda_1240525-16383.jpg" alt="Avatar contento">
    <h1>Ana Pérez</h1>
    <p>¡Hola! Me encanta el desarrollo web y los videojuegos de aventuras.</p>

    <h2>Mis Enlaces</h2>
    <ul>
      <li><a href="https://github.com">Mi GitHub</a></li>
      <li><a href="https://ejemplo.com">Mi Blog</a></li>
    </ul>
  </div>

</body>
</html>
```

**CSS (style.css):**
```css
body {
  font-family: "Arial", sans-serif;
  background-color: #fce4ec;
  padding-top: 40px;
  margin: 0;
}

.tarjeta-perfil {
  background-color: white;
  width: 300px;
  margin: auto;
  padding: 30px;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
}

img {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 15px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin: 10px 0;
}

a {
  color: #c2185b;
}
```

- **Plantilla inicial de la lección:** [lesson-8/starter/index.html](../../lesson-8/starter/index.html)
- **Código elaborado en clase:** [lesson-8/completed/index.html](../../lesson-8/completed/index.html)

---