# Espacios y Bordes

## Video de la Clase y Entorno de Práctica

*Enlace al video de YouTube:* [**falta**](falta)

Para esta clase continuaremos usando **CodePen**, el mismo entorno en línea que usamos la clase pasada. No necesitas instalar nada en tu computadora. Haz clic en el siguiente enlace para abrir el código inicial de la clase ya precargado: [**https://codepen.io/ST-A-the-encoder/pen/wBoXzwR**](https://codepen.io/ST-A-the-encoder/pen/wBoXzwR)

Al igual que en la clase anterior, verás la interfaz con los panales divididos.

![Captura de CodePen con el proyecto precargado](../assets/lesson-07/codepen-precargado.png){width=80%}

## Notas de la Clase

Nuestra aplicación va tomando forma, pero tiene un problema: todo está pegado a los bordes. ¡Nuestros textos necesitan respirar! Hoy aprenderemos a darle espacio a las cosas y a ponerles marcos.

**¿Qué es un div y por qué lo usamos?**

Antes de hablar de bordes y espacios, veamos esta etiqueta: `<div>`. Un div es como una caja o contenedor que nos permite agrupar varios elementos. En este caso, nuestro div guarda el título `<h1>` y el párrafo `<p>`. Gracias a eso, en lugar de mover o decorar cada elemento por separado, podemos aplicar estilos a toda la caja completa. La clase mi-caja nos ayuda a identificar este contenedor para darle diseño con CSS.

```html
<div>
  <h1></h1>
  <p></p>
</div>
```

**La Teoría de las Cajas**

En la web, absolutamente todo es una caja invisible. Cada foto, cada título y cada párrafo vive dentro de su propia caja. Y nosotros podemos controlar el tamaño de esa caja y qué tan lejos está de sus vecinas. Para ver estas cajas, pongamos un borde a nuestro título con la propiedad `border`. Escribimos `border: 2px solid black;`. ¡Ahí está la caja! Pero el texto está tocando el borde negro. Para darle espacio interior, usamos la propiedad `padding`. Si agregamos `padding: 20px;`, vemos cómo la caja se hace gordita y empuja los bordes hacia afuera.

Antes de continuar, detengámonos un momento en esta línea:
```css
border: 2px solid black;
```
Aunque parece una sola instrucción, en realidad tiene tres partes. `2px` indica el grosor del borde; en este caso, será una línea delgada de 2 píxeles. `solid` indica el tipo de línea; significa que el borde será continuo, no punteado ni cortado. Y `black` indica el color del borde. Entonces, esta línea le dice al navegador: crea un borde negro, continuo y de 2 píxeles alrededor del elemento.

**Margen (El Espacio Exterior)**

¿Y qué pasa si queremos alejar nuestra caja de las demás cajas? Usamos el margen o `margin`. Mientras que el padding empuja hacia adentro, el margen empuja hacia afuera. Si al párrafo de abajo le ponemos `margin-top: 30px;`, le estamos diciendo: '¡Aléjate 30 píxeles para arriba!'.

**El Truco Mágico: Centrar Bloques**

Te enseñaremos uno de los trucos más valiosos. Para centrar toda una caja en medio de la pantalla (no solo el texto, sino el objeto entero), primero le damos un ancho fijo, como `width: 50%;`. Luego, aplicamos la magia: `margin: auto;`. Esto le dice al navegador que reparta el espacio sobrante equitativamente a los lados.

**margin-top, margin-bottom y separación exterior**

Además de usar `margin: auto;`, también podemos controlar márgenes específicos. Por ejemplo, `margin-top: 50px;` agrega espacio exterior por arriba, separando la caja del borde superior de la pantalla. Si quisiéramos separar la caja de algo que está debajo, podríamos usar `margin-bottom: 30px;`. La idea es simple: "top" controla arriba, "bottom" controla abajo, "left" controla izquierda y "right" controla derecha. Así podemos decidir exactamente dónde queremos más espacio.

## Actividad Práctica de la Clase: 

**El Reto del Ancho Adecuado:**

Ahora es tu turno. Cambia el `width`. Prueba `80%`, luego `40%` y vuelve a `60%`. Observa cómo cambia el ancho de la caja y cómo sigue centrada gracias a `margin: auto;`. Esta prueba te ayuda a sentir cómo responde el diseño.

## Recomendaciones y Errores Comunes para Principiantes

Si escribes `margin: auto;` y no ves que la caja se centre, revisa si tiene un ancho definido. También revisa si estás aplicando la regla al elemento correcto. En nuestro caso, la regla está en `div`, porque el `div` es la caja que contiene el título y el párrafo.

## Recursos Complementarios de la Clase

- **Código HTML inicial de la lección:** [starter-files/lesson-07/index.html](https://github.com/upc-pre-1asi0730-2610-10215-arcadiadevs/webdev-course-arcadiadevs/blob/main/starter-files/lesson-07/index.html)
- **Código CSS inicial de la lección:** [starter-files/lesson-07/styles.css](https://github.com/upc-pre-1asi0730-2610-10215-arcadiadevs/webdev-course-arcadiadevs/blob/main/starter-files/lesson-07/styles.css)
- **Código HTML final de la lección:** [completed-examples/lesson-07/index.html](https://github.com/upc-pre-1asi0730-2610-10215-arcadiadevs/webdev-course-arcadiadevs/blob/main/completed-examples/lesson-07/index.html)
- **Código CSS final de la lección:** [completed-examples/lesson-07/styles.css](https://github.com/upc-pre-1asi0730-2610-10215-arcadiadevs/webdev-course-arcadiadevs/blob/main/completed-examples/lesson-07/styles.css)