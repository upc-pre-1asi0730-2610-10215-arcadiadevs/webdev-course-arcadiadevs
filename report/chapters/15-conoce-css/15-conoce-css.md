# Lección 5: Conoce a CSS

## 1. Ficha Técnica

* **Duración estimada:** 7 minutos.
* **Objetivo de aprendizaje:** Comprender la sintaxis básica de CSS mediante el uso de selectores de etiquetas, declaraciones (propiedades y valores), y cómo se relacionan los estilos con los elementos del HTML creados anteriormente.

## 2. Guion de Video

**[Escena 1: El momento del diseño]**

* *(Visual: El instructor sostiene una brocha de pintura. La pantalla muestra un HTML blanco y negro, y luego se llena de colores vivos).*
* **Instructor (Audio):** "Hasta ahora, hemos construido un excelente esqueleto para nuestra aplicación usando HTML. Sin embargo, no tiene mucho estilo. ¡Es hora de pintar y decorar nuestra casa! Hoy vamos a conocer oficialmente a CSS (que significa *Hojas de Estilo en Cascada*, por sus siglas en inglés)."

**[Escena 2: La regla CSS (El Selector)]**

* *(Visual: Transición al entorno de CodePen. El instructor señala el panel CSS vació).*
* **Instructor (Audio):** "A diferencia de HTML, en CSS no usamos etiquetas con < >. Usamos algo llamado 'reglas'. Para empezar, debemos decirle a CSS a quién queremos pintar. A esto se le llama **selector**. Si queremos pintar el fondo de toda la página, le decimos: ¡Oye, body! Ven para acá."
* *(Visual: Escribe la palabra body en el panel de CSS).*

**[Escena 3: Las Llaves (El espacio de trabajo)]**

* *(Visual: Al lado de la palabra body se abren dos llaves { }).*
* **Instructor (Audio):** "Una vez que llamamos a nuestro selector, abrimos unas llaves { }. Todo lo que escribamos dentro de estas llaves será la lista de instrucciones de diseño exclusivamente para ese elemento."

**[Escena 4: Propiedades y Valores]**

* *(Visual: Se escribe la propiedad background-color y el valor lightblue, cerrando con punto y coma). El fondo de todo el HTML cambia de blanco a azul claro.*
* **Instructor (Audio):** "Ahora le damos nuestra instrucción. En CSS, las instrucciones se dividen en dos: la propiedad (qué queremos cambiar) y el valor (cómo queremos que se vea). Le diremos background-color (propiedad) luego dos puntos :, seguido de lightblue (el valor). ¡Y un requisito súper importante! Siempre, siempre terminamos la instrucción con un punto y coma ;."

**[Escena 5: Estilizando el Texto]**

* *(Visual: Escribe otra regla abajo llamando al selector h1 y cambiando el color del texto).*
* **Instructor (Audio):** "Hagamos lo mismo con nuestro título. Llamamos al selector h1, abrimos las llaves, usamos la propiedad color y le damos un valor, digamos... ¡darkblue!. Y boom, nuestro título principal ahora tiene más vida."

### Bloque C: Tipos de selectores básicos (75-90 segundos)

* *(Visual: En pantalla aparecen tres ejemplos lado a lado: `h1`, `.destacado` y `#principal`. Cada uno ilumina una parte distinta del HTML.)*
* **Instructor (Audio):** "Hasta ahora usamos un selector de etiqueta, como `body` o `h1`. Eso significa que CSS busca todas las etiquetas con ese nombre y les aplica el estilo. Pero CSS tiene más formas de seleccionar elementos. Por ejemplo, si usamos `.destacado`, estamos llamando a una clase. Las clases sirven cuando queremos aplicar el mismo estilo a varios elementos diferentes. En HTML se vería como `class="destacado"`. También existe el selector con numeral, como `#principal`, que se usa para un identificador único escrito como `id="principal"`. Para empezar, quédate con esta idea: la etiqueta sirve para estilos generales, la clase sirve para reutilizar estilos, y el id sirve para un elemento muy específico."


### Bloque C.1: Mini ejemplo de selector de clase (45-60 segundos)

* *(Visual: Se añade un párrafo con `class="importante"` y luego se escribe `.importante { color: red; }` en CSS.)*
* **Instructor (Audio):** "Veamos un ejemplo rápido. Si tengo varios párrafos, pero solo quiero que uno se vea diferente, no necesito cambiar todos los `<p>`. Puedo agregarle una clase al párrafo especial: `class="importante"`. Luego, en CSS, escribo `.importante`, con un punto al inicio, abro llaves y le doy un color. Así le digo al navegador: 'busca el elemento que tenga esta clase y aplícale este estilo'. Este detalle será muy útil cuando tu página crezca y tengas muchos elementos."

### Bloque D: Colores en inglés y códigos hexadecimales (45-60 segundos)

* *(Visual: Se prueba `pink`, luego `lightgreen`, luego `#fce4ec`.)*
* **Instructor (Audio):** "Para los colores, CSS acepta nombres en inglés como `red`, `blue`, `pink` o `lightgreen`. También acepta códigos de color, como `#fce4ec` (códigos en base hexadecimal). Por ahora puedes usar nombres porque son más fáciles de recordar. Más adelante, los códigos te permitirán elegir tonos más exactos."

### Bloque E: Contraste y legibilidad (60 segundos)

* *(Visual: Texto amarillo sobre fondo blanco con una equis; texto oscuro sobre fondo claro con un check.)*
* **Instructor (Audio):** "No todos los colores funcionan bien juntos. Si el fondo es muy claro y el texto también es claro, será difícil leer. Un buen diseño no solo se ve bonito: también se entiende. Antes de elegir colores, revisa si puedes leer el texto sin esfuerzo. Si tienes que acercarte demasiado a la pantalla, quizá necesitas más contraste."

### Bloque F: Pausa práctica guiada (45 segundos)

* *(Visual: Texto: 'Pausa: cambia el fondo y el título'.)*
* **Instructor (Audio):** "Pausa el video y prueba dos combinaciones. Primero cambia el fondo del `body`. Luego cambia el color del `h1`. Observa qué combinaciones se ven bien y cuáles no. Esta exploración es parte del aprendizaje: CSS se entiende mucho mejor probando."

### Bloque G: Error común en CSS (60 segundos)

* *(Visual: Código sin `;`, sin `:` o con llave faltante. Luego se corrige.)*
* **Instructor (Audio):** "Cuando CSS no funciona, revisa la puntuación. ¿Pusiste dos puntos entre propiedad y valor? ¿Terminaste con punto y coma? ¿Cerraste las llaves? Estos símbolos parecen pequeños, pero CSS los necesita para entender tus instrucciones. Si una regla no se aplica, muchas veces el problema está en un detalle de escritura."

### Bloque H: Formas de escribir CSS en una página (75-90 segundos)

* *(Visual: Tres tarjetas: "Panel CSS / archivo CSS", "`<style>` en `<head>`", y "`style` dentro de una etiqueta". Se marca con check la opción del panel CSS para este curso.)*
* **Instructor (Audio):** "Antes de cerrar, hay algo importante: existen varias formas de escribir CSS. En CodePen tenemos un panel CSS separado, que se parece a trabajar con un archivo propio de estilos. Esa suele ser la forma más ordenada, porque mantiene el HTML por un lado y el diseño por otro. También podríamos escribir CSS dentro de una etiqueta `<style>` en la parte `<head>` del HTML. Eso funciona para ejemplos pequeños, pero si la página crece puede volverse difícil de organizar."

### Bloque I: El atributo `style` y por qué no abusar de él (60 segundos)

* *Visual: Se muestra una etiqueta p con inline*
* **Instructor (Audio):** "También existe el atributo `style`, que se escribe directamente dentro de una etiqueta HTML. Esto cambia solo ese elemento específico. Es rápido para probar, pero no conviene usarlo demasiado, porque mezcla contenido con diseño y hace que el código sea más difícil de mantener. En este curso usaremos principalmente el panel de CSS, porque queremos practicar la separación entre estructura y apariencia."

### Bloque J: Cierre ampliado (30-45 segundos)

* *(Visual: Resumen: selector, propiedad, valor.)*
* **Instructor (Audio):** "Hoy conociste la forma básica de una regla CSS. El selector elige el elemento, la propiedad indica qué cambia y el valor define cómo cambia. En la siguiente lección usaremos CSS para mejorar la lectura con tipografía, tamaño y alineación."


## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<html lang="es">
  <body>
    <h1>Mi primera web con estilo</h1>
    <p>Estoy aprendiendo a separar la estructura del diseño. Es genial ver cómo cambia de color.</p>
  </body>
</html>
`

**CSS:**
`css
/* Escribe aquí tu primera regla para el 'body' */


/* Escribe aquí tu regla para el título 'h1' */

`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <body>
    <h1>Mi primera web con estilo</h1>
    <p>Estoy aprendiendo a separar la estructura del diseño. Es genial ver cómo cambia de color.</p>
  </body>
</html>
`

**CSS:**
`css
/* Regla para el fondo de pantalla */
body {
  background-color: #fce4ec; /* un rosa pastel, pero también puede ser un color en inglés como 'pink' */
}

/* Regla para el texto del título */
h1 {
  color: #880e4f;
}

/* Reto adicional completado: Regla para el párrafo */
p {
  color: #4a4a4a;
}
`

## 5. Actividad Práctica

**Reto (6 minutos): ¡Pinta tu aplicación!**
1. En el panel de CSS, crea un selector para el ody.
2. Dentro de las llaves { }, utiliza la propiedad ackground-color y escribe un color en inglés (yellow, lightgreen, coral, etc.). No olvides cerrar con ;.
3. Crea un nuevo selector, pero esta vez para el h1 (el título). 
4. Usa la propiedad color y asígnale un color que haga contraste con el fondo.
5. (Extra): Intenta crear un tercer selector para el <p> (párrafo) y ponle un color distinto. ¡Revisa que no falte ningún punto y coma!
---

