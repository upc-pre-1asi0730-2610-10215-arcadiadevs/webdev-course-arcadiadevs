# Lección 7: Espacios y bordes

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Comprender y aplicar el modelo de caja de CSS (*Box Model*) usando propiedades como `margin`, `padding`, `border`, y aprender a centrar elementos usando `margin: auto;`.

---

## 2. Guion de Video

**[Escena 1: El Síndrome del Todo Apretado]**
- *(Visual: El instructor sonríe. Aparece una pantalla web de ejemplo donde todo el texto e imágenes están pegados al borde izquierdo de la pantalla).*
- **Instructor (Audio):** "Nuestra aplicación va tomando forma, pero tiene un problema: todo está pegado a los bordes. ¡Nuestros textos necesitan respirar! Hoy aprenderemos a darle espacio a las cosas y a ponerles marcos."

### Bloque B: ¿Qué es un div y por qué lo usamos? (75 segundos)
Instructor (Audio): "Antes de hablar de bordes y espacios, veamos esta etiqueta: `<div>`. Un div es como una caja o contenedor que nos permite agrupar varios elementos. En este caso, nuestro div guarda el título `<h1>` y el párrafo `<p>`. Gracias a eso, en lugar de mover o decorar cada elemento por separado, podemos aplicar estilos a toda la caja completa. La clase mi-caja nos ayuda a identificar este contenedor para darle diseño con CSS.

**[Escena 2: La Teoría de las Cajas]**

- *(Visual: Animación donde un párrafo de texto se encierra en una caja invisible roja).*
- **Instructor (Audio):** "En la web, absolutamente todo es una caja invisible. Cada foto, cada título y cada párrafo vive dentro de su propia caja. Y nosotros podemos controlar el tamaño de esa caja y qué tan lejos está de sus vecinas."

**[Escena 3: Bordes y Padding (El Espacio Interior)]**
- *(Visual: Pantalla de CodePen. Se añade un borde y luego un padding al h1).*
- **Instructor (Audio):** "Para ver estas cajas, pongamos un borde a nuestro título con la propiedad `border`. Escribimos `border: 2px solid black;`. ¡Ahí está la caja! Pero el texto está tocando el borde negro. Para darle espacio interior, usamos la propiedad `padding`. Si agregamos `padding: 20px;`, vemos cómo la caja se hace gordita y empuja los bordes hacia afuera."

###  Bloque C: Entendiendo border: 2px solid black; (60-75 segundos)
(Visual: En CodePen se resalta la línea border: 2px solid black; y se divide visualmente en tres partes: 2px, solid y black.)
Instructor (Audio): "Antes de continuar, detengámonos un momento en esta línea: border: 2px solid black;. Aunque parece una sola instrucción, en realidad tiene tres partes. 2px indica el grosor del borde; en este caso, será una línea delgada de 2 píxeles. solid indica el tipo de línea; significa que el borde será continuo, no punteado ni cortado. Y black indica el color del borde. Entonces, esta línea le dice al navegador: crea un borde negro, continuo y de 2 píxeles alrededor del elemento."

**[Escena 4: Margen (El Espacio Exterior)]**
- *(Visual: Aparecen dos cajas pegadas, y se agrega margin para separarlas).*
- **Instructor (Audio):** "¿Y qué pasa si queremos alejar nuestra caja de las demás cajas? Usamos el margen o `margin`. Mientras que el padding empuja hacia adentro, el margen empuja hacia afuera. Si al párrafo de abajo le ponemos `margin-top: 30px;`, le estamos diciendo: '¡Aléjate 30 píxeles para arriba!'."
 
**[Escena 5: El truco mágico: Centrar bloques]**
- *(Visual: Una caja ancha en CodePen se desliza al centro perfecto de la pantalla).*
- **Instructor (Audio):** "Te enseñaré uno de los trucos más valiosos. Para centrar toda una caja en medio de la pantalla (no solo el texto, sino el objeto entero), primero le damos un ancho fijo, como `width: 50%;`. Luego, aplicamos la magia: `margin: auto;`. Esto le dice al navegador que reparta el espacio sobrante equitativamente a los lados."

### Bloque F: margin-top, margin-bottom y separación exterior (60-75 segundos)
(Visual: Se agrega margin-top: 50px; y la caja baja. Luego se muestra un ejemplo opcional con margin-bottom: 30px;.)
Instructor (Audio): "Además de usar margin: auto;, también podemos controlar márgenes específicos. Por ejemplo, margin-top: 50px; agrega espacio exterior por arriba, separando la caja del borde superior de la pantalla. Si quisiéramos separar la caja de algo que está debajo, podríamos usar margin-bottom: 30px;. La idea es simple: top controla arriba, bottom controla abajo, left controla izquierda y right controla derecha. Así podemos decidir exactamente dónde queremos más espacio."

### Bloque G: Pausa práctica guiada (45 segundos)
- *(Visual: Texto en pantalla: 'Pausa: cambia 60% por 80% y 40%'.)*
- **Instructor (Audio):** "Ahora es tu turno! Cambia el `width`. Prueba `80%`, luego `40%` y vuelve a `60%`. Observa cómo cambia el ancho de la caja y cómo sigue centrada gracias a `margin: auto;`. Esta prueba te ayuda a sentir cómo responde el diseño."

### Bloque H: Error común con márgenes (45-60 segundos)
- *(Visual: Código con `margin: auto` pero sin `width`. Luego se corrige.)*
- **Instructor (Audio):** "Si escribes `margin: auto;` y no ves que la caja se centre, revisa si tiene un ancho definido. También revisa si estás aplicando la regla al elemento correcto. En nuestro caso, la regla está en `div`, porque el `div` es la caja que contiene el título y el párrafo."

### Bloque I: Cierre ampliado (30-45 segundos)
- *(Visual: Resumen: `border` muestra la caja, `padding` separa por dentro, `margin` separa por fuera.)*
- **Instructor (Audio):** "Hoy aprendiste a controlar el espacio. El borde nos muestra la caja, el padding da aire interior y el margin separa la caja del exterior. Con esto ya tienes una herramienta clave para que tu proyecto final no se vea apretado ni desordenado."

---

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
```html
<html lang="es">
  <body>
    <div class="mi-caja">
      <h1>Mis Películas</h1>
      <p>Estas son algunas de las cintas que más me han impactado a lo largo de mi vida.</p>
    </div>
  </body>
</html>
```

**CSS:**
```css
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
```
