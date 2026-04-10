# Lección 7: Espacios y bordes

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Comprender y aplicar el modelo de caja de CSS (*Box Model*) usando propiedades como margin, padding, order, y aprender a centrar elementos usando margin: auto;.

## 2. Guion de Video

**[Escena 1: El Síndrome del Todo Apretado]**
- *(Visual: El instructor sonríe. Aparece una pantalla web de ejemplo donde todo el texto e imágenes están pegados al borde izquierdo de la pantalla, ahogando la vista).*
- **Instructor (Audio):** "Nuestra aplicación va tomando forma, pero tiene un problema: todo está pegado a los bordes. ¡Nuestros textos necesitan respirar! Hoy aprenderemos a darle espacio a las cosas y a ponerles marcos."

**[Escena 2: La Teoría de las Cajas]**
- *(Visual: Animación donde un párrafo de texto se encierra en una caja invisible roja).*
- **Instructor (Audio):** "En la web, absolutamente todo es una caja invisible. Cada foto, cada título y cada párrafo vive dentro de su propia caja. Y nosotros podemos controlar el tamaño de esa caja y qué tan lejos está de sus vecinas."

**[Escena 3: Bordes y Padding (El Espacio Interior)]**
- *(Visual: Pantalla de CodePen. Se añade un borde y luego un padding al h1).*
- **Instructor (Audio):** "Para ver estas cajas, pongamos un borde a nuestro título con la propiedad order. Escribimos order: 2px solid black;. ¡Ahí está la caja! Pero el texto está tocando el borde negro. Para darle espacio interior, usamos la propiedad padding. Si agregamos padding: 20px;, vemos cómo la caja se hace gordita y empuja los bordes hacia afuera."

**[Escena 4: Margen (El Espacio Exterior)]**
- *(Visual: Aparecen dos cajas pegadas, y se agrega margin para separarlas).*
- **Instructor (Audio):** "¿Y qué pasa si queremos alejar nuestra caja de las demás cajas? Usamos el margen o margin. Mientras que el padding empuja hacia adentro, el margen empuja hacia afuera. Si al párrafo de abajo le ponemos margin-top: 30px;, le estamos diciendo: '¡Aléjate 30 píxeles por arriba!'."

**[Escena 5: El truco mágico: Centrar bloques]**
- *(Visual: Una caja ancha en CodePen se desliza al centro perfecto de la pantalla).*
- **Instructor (Audio):** "Te enseñaré uno de los trucos más valiosos. Para centrar toda una caja en medio de la pantalla (no solo el texto, sino el objeto entero), primero le damos un ancho fijo, como width: 50%;. Luego, aplicamos la magia: margin: auto;. Esto le dice al navegador que reparta el espacio sobrante equitativamente a los lados."

**[Escena 6: Cierre y Reto]**
- *(Visual: El instructor despide animado. Texto: "Reto: Dale respiro a tu web").*
- **Instructor (Audio):** "Controlar el espacio es el requisito más fuerte de un diseño profesional. En nuestro reto final antes del gran proyecto, aprenderás a usar estas cajas a tu favor. ¡A practicar!"

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<html lang="es">
  <body>
    <div class="mi-caja">
      <h1>Mis Películas</h1>
      <p>Estas son algunas de las cintas que más me han impactado a lo largo de mi vida.</p>
    </div>
  </body>
</html>
`

**CSS:**
`css
body {
  font-family: Arial, sans-serif;
  background-color: #e0f7fa;
}

div {
  background-color: white;
  /* 1. Añade un borde a la caja */
  
  /* 2. Añade padding (espacio interno) */
  
  /* 3. Limita el ancho de la caja con width */
  
  /* 4. ¡Usa el truco mágico para centrarla (margin)! */
  
}
`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <body>
    <div class="mi-caja">
      <h1>Mis Películas</h1>
      <p>Estas son algunas de las cintas que más me han impactado a lo largo de mi vida.</p>
    </div>
  </body>
</html>
`

**CSS:**
`css
body {
  font-family: Arial, sans-serif;
  background-color: #e0f7fa;
}

div {
  background-color: white;
  /* 1. Añade un borde a la caja */
  border: 3px solid #00acc1;
  /* 2. Añade padding para que el texto no toque el borde */
  padding: 30px;
  /* 3. Limita el ancho para que no ocupe toda la pantalla */
  width: 60%;
  /* 4. Truco mágico para centrar horizontalmente */
  margin: auto;
  /* Separando un poco la caja entera del techo */
  margin-top: 50px;
}
`

## 5. Actividad Práctica

**Reto (5 minutos): ¡Domina las Cajas!**
1. En CodePen, ve a las reglas de CSS de la etiqueta div. Esta etiqueta es literalmente "una caja gigante" que guarda nuestro texto.
2. Ponle un borde (order: 3px solid black;).
3. Agrega espacio interno para que el texto no toque el borde negro. Usa padding: 30px;.
4. Achica un poco la caja poniendo width: 60%;.
5. Usa el truco de oro: margin: auto; para centrar perfectamente esa caja en la pantalla de tu aplicación. 
6. (Extra) Añade espacio por arriba a la caja usando margin-top: 50px;.
