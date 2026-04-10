# Lección 5: Conoce a CSS

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Comprender la sintaxis básica de CSS mediante el uso de selectores de etiquetas, declaraciones (propiedades y valores), y cómo se relacionan los estilos con los elementos del HTML creados anteriormente.

## 2. Guion de Video

**[Escena 1: El momento del diseño]**
- *(Visual: El instructor sostiene una brocha de pintura. La pantalla muestra un HTML blanco y negro, y luego se llena de colores vivos).*
- **Instructor (Audio):** "Hasta ahora, hemos construido un excelente esqueleto para nuestra aplicación usando HTML. Sin embargo, no tiene mucho estilo. ¡Es hora de pintar y decorar nuestra casa! Hoy vamos a conocer oficialmente a CSS (que significa *Hojas de Estilo en Cascada*, por sus siglas en inglés)."

**[Escena 2: La regla CSS (El Selector)]**
- *(Visual: Transición al entorno de CodePen. El instructor señala el panel CSS vació).*
- **Instructor (Audio):** "A diferencia de HTML, en CSS no usamos etiquetas con < >. Usamos algo llamado 'reglas'. Para empezar, debemos decirle a CSS a quién queremos pintar. A esto se le llama **selector**. Si queremos pintar el fondo de toda la página, le decimos: ¡Oye, ody! Ven para acá."
- *(Visual: Escribe la palabra ody en el panel de CSS).*

**[Escena 3: Las Llaves (El espacio de trabajo)]**
- *(Visual: Al lado de la palabra ody se abren dos llaves { }).*
- **Instructor (Audio):** "Una vez que llamamos a nuestro selector, abrimos unas llaves { }. Todo lo que escribamos dentro de estas llaves será la lista de instrucciones de diseño exclusivamente para ese elemento."

**[Escena 4: Propiedades y Valores]**
- *(Visual: Se escribe la propiedad ackground-color y el valor lightblue, cerrando con punto y coma). El fondo de todo el HTML cambia de blanco a azul claro.*
- **Instructor (Audio):** "Ahora le damos nuestra instrucción. En CSS, las instrucciones se dividen en dos: la propiedad (qué queremos cambiar) y el valor (cómo queremos que se vea). Le diremos ackground-color (propiedad) luego dos puntos :, seguido de lightblue (el valor). ¡Y un requisito súper importante! Siempre, siempre terminamos la instrucción con un punto y coma ;."

**[Escena 5: Estilizando el Texto]**
- *(Visual: Escribe otra regla abajo llamando al selector h1 y cambiando el color del texto).*
- **Instructor (Audio):** "Hagamos lo mismo con nuestro título. Llamamos al selector h1, abrimos las llaves, usamos la propiedad color y le damos un valor, digamos... ¡darkblue!. Y boom, nuestro título principal ahora tiene más vida."

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor animado apuntando al espectador. Texto: "Reto: Ponle tu estilo").*
- **Instructor (Audio):** "Con HTML creamos las cajas, y con CSS decidimos cómo se ven. Este es el primer paso para crear diseños increíbles. Ve a tu CodePen y completa el reto. ¡Nos vemos en la próxima clase!"

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
