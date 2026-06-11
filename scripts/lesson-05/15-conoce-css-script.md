# Lección 5: Conoce a CSS

## 1. Estructura de Carpetas

Sugerimos organizar esta lección en el repositorio de la siguiente manera:

```text
/starter-files/lesson-05        # Archivo base listo para escribir el código en vivo
├── index.html
└── styles.css
/completed-examples/lesson-05   # El código final con las reglas CSS aplicadas correctamente
├── index.html
└── styles.css
```

## 2. Guion de Video

> **Introducción: Es hora de decorar**
> Hasta ahora, hemos construido un excelente esqueleto para nuestra aplicación usando HTML. Sin embargo, no tiene mucho estilo. ¡Es hora de pintar y decorar nuestra casa! Hoy vamos a conocer oficialmente a CSS (que significa *Hojas de Estilo en Cascada*, por sus siglas en inglés).
>
> **La Regla CSS y el Selector**
> A diferencia de HTML, en CSS no usamos etiquetas con < >. Usamos algo llamado 'reglas'. Para empezar, debemos decirle a CSS a quién queremos pintar. A esto se le llama **selector**. Si queremos pintar el fondo de toda la página, le decimos: ¡Oye, body! Ven para acá.
> 
> **Las Llaves: Nuestro Espacio de Trabajo**
> Una vez que llamamos a nuestro selector, abrimos unas llaves { }. Todo lo que escribamos dentro de estas llaves será la lista de instrucciones de diseño exclusivamente para ese elemento.
> **Propiedades y Valores**
> Ahora le damos nuestra instrucción. En CSS, las instrucciones se dividen en dos: la propiedad (qué queremos cambiar) y el valor (cómo queremos que se vea). Le diremos background-color (propiedad) luego dos puntos :, seguido de lightblue (el valor). ¡Y un requisito súper importante! Siempre, siempre terminamos la instrucción con un punto y coma ;.
>
> **Tipos de selectores básicos**
> Hasta ahora usamos un selector de etiqueta, como `body` o `h1`. Eso significa que CSS busca todas las etiquetas con ese nombre y les aplica el estilo. Pero CSS tiene más formas de seleccionar elementos. Por ejemplo, si usamos `.destacado`, estamos llamando a una clase. Las clases sirven cuando queremos aplicar el mismo estilo a varios elementos diferentes. En HTML se vería como `class="destacado"`. También existe el selector con numeral, como `#principal`, que se usa para un identificador único escrito como `id="principal"`. Para empezar, quédate con esta idea: la etiqueta sirve para estilos generales, la clase sirve para reutilizar estilos, y el id sirve para un elemento muy específico.
>
> **Mini ejemplo de selector de clase**
> Veamos un ejemplo rápido. Si tengo varios párrafos, pero solo quiero que uno se vea diferente, no necesito cambiar todos los `<p>`. Puedo agregarle una clase al párrafo especial: `class="importante"`. Luego, en CSS, escribo `.importante`, con un punto al inicio, abro llaves y le doy un color. Así le digo al navegador: 'busca el elemento que tenga esta clase y aplícale este estilo'. Este detalle será muy útil cuando tu página crezca y tengas muchos elementos.
>
> **Colores en inglés y códigos hexadecimales**
> Para los colores, CSS acepta nombres en inglés como `red`, `blue`, `pink` o `lightgreen`. También acepta códigos de color, como `#fce4ec` (códigos en base hexadecimal). Por ahora puedes usar nombres porque son más fáciles de recordar. Más adelante, los códigos te permitirán elegir tonos más exactos.
>
> **Contraste y legibilidad**
> No todos los colores funcionan bien juntos. Si el fondo es muy claro y el texto también es claro, será difícil leer. Un buen diseño no solo se ve bonito: también se entiende. Antes de elegir colores, revisa si puedes leer el texto sin esfuerzo. Si tienes que acercarte demasiado a la pantalla, quizá necesitas más contraste.
>
> **Pausa práctica guiada**
> Pausa el video y prueba dos combinaciones. Primero cambia el fondo del `body`. Luego cambia el color del `h1`. Observa qué combinaciones se ven bien y cuáles no. Esta exploración es parte del aprendizaje: CSS se entiende mucho mejor probando.
>
> **Error común en CSS**
> Cuando CSS no funciona, revisa la puntuación. ¿Pusiste dos puntos entre propiedad y valor? ¿Terminaste con punto y coma? ¿Cerraste las llaves? Estos símbolos parecen pequeños, pero CSS los necesita para entender tus instrucciones. Si una regla no se aplica, muchas veces el problema está en un detalle de escritura.
>
> **Formas de escribir CSS en una página**
> Antes de cerrar, hay algo importante: existen varias formas de escribir CSS. En CodePen tenemos un panel CSS separado, que se parece a trabajar con un archivo propio de estilos. Esa suele ser la forma más ordenada, porque mantiene el HTML por un lado y el diseño por otro. También podríamos escribir CSS dentro de una etiqueta `<style>` en la parte `<head>` del HTML. Eso funciona para ejemplos pequeños, pero si la página crece puede volverse difícil de organizar.
>
> **El atributo `style` y por qué no abusar de él**
> También existe el atributo `style`, que se escribe directamente dentro de una etiqueta HTML. Esto cambia solo ese elemento específico. Es rápido para probar, pero no conviene usarlo demasiado, porque mezcla contenido con diseño y hace que el código sea más difícil de mantener. En este curso usaremos principalmente el panel de CSS, porque queremos practicar la separación entre estructura y apariencia.
>
> **Cierre ampliado**
> Hoy conociste la forma básica de una regla CSS. El selector elige el elemento, la propiedad indica qué cambia y el valor define cómo cambia. En la siguiente lección usaremos CSS para mejorar la lectura con tipografía, tamaño y alineación.
> 
