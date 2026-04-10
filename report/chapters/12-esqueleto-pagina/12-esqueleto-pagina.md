# Lección 2: El esqueleto de tu página

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Identificar y redactar la estructura básica de un documento HTML (<html>, <head>, <body>), comprendiendo el concepto de etiquetas anidadas y atributos.

## 2. Guion de Video

**[Escena 1: Introducción al Esqueleto Humano]**
- *(Visual: El instructor saluda. Aparece la silueta de una persona dividida en cabeza y cuerpo).*
- **Instructor (Audio):** "¡Hola de nuevo! En la lección anterior escribimos código directamente, pero para que un navegador entienda nuestra página correctamente, necesitamos darle una estructura formal. Al igual que nosotros, una página web tiene una 'cabeza' y un 'cuerpo'."

**[Escena 2: La Etiqueta Principal]**
- *(Visual: Pantalla de CodePen vacía. El instructor empieza a escribir <html> y </html>).*
- **Instructor (Audio):** "Todo empieza con la etiqueta <html>. Esta etiqueta abraza a todo el contenido de nuestra página. Además, podemos darle un 'atributo' para decirle al navegador en qué idioma estamos escribiendo. Para español, usamos el atributo lang y le damos el valor 'es'."

**[Escena 3: La Cabeza (El cerebro de la página)]**
- *(Visual: Se escribe la etiqueta <head> dentro de <html>).*
- **Instructor (Audio):** "Dentro del HTML, tenemos la etiqueta <head>. Imagina que es el cerebro. Aquí va información importante para el navegador, pero que normalmente no se ve en la pantalla principal. ¿Ves el nombre de la pestaña en tu navegador? Eso lo creamos aquí adentro, usando la etiqueta <title>."

**[Escena 4: El Cuerpo (Lo que todos ven)]**
- *(Visual: Se escribe la etiqueta <body> debajo del <head>. Se añade un <h1> y un <p>).*
- **Instructor (Audio):** "Luego viene el <body>, el cuerpo. Aquí es donde ponemos todo lo que queremos que nuestros visitantes vean: textos, imágenes y colores. Escribamos un título y un pequeño párrafo."

**[Escena 5: Repaso del Código y Visualización]**
- *(Visual: Se muestra el código completo bien ordenado (indentado). Una flecha señala cómo las etiquetas se abren y se cierran).*
- **Instructor (Audio):** "Fíjate cómo las etiquetas se abren y se cierran con una barra inclinada /. Es como abrir una caja, poner contenido dentro y luego cerrarla. Mantener este esqueleto ordenado es un requisito clave para que nuestra aplicación funcione perfecta en cualquier dispositivo."

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor en cámara sonriendo. Texto: "Reto: Construye tu esqueleto").*
- **Instructor (Audio):** "¡Gran trabajo! Ahora ya conoces la anatomía de la web. En la sección práctica, tu misión será construir este esqueleto desde cero. ¡Inténtalo y nos vemos en la próxima lección para organizar mejor nuestra información!"

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<!-- Escribe aquí tu estructura básica HTML -->

`

**CSS:**
`css
/* Hoy no usaremos CSS, ¡solo estructura! */
`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <head>
    <title>La web de mis hobbies</title>
  </head>
  <body>
    <h1>¡Bienvenidos a mi primera web formal!</h1>
    <p>Me encanta aprender desarrollo web. Este es el cuerpo de mi página.</p>
  </body>
</html>
`

**CSS:**
`css
/* Vacío por ahora */
`

## 5. Actividad Práctica

**Reto (5 minutos): ¡Arma el Esqueleto!**
1. Abre el CodePen de inicio.
2. Escribe la etiqueta <html> y añádele el atributo lang="es".
3. Dentro, crea el <head> y ponle un <title> que diga de qué tratará tu página (ej. "La web de mis hobbies").
4. Crea el <body> y dentro de él, escribe un título (<h1>) dándoles la bienvenida a tus visitantes.
5. Agrega un párrafo (<p>) contando un pasatiempo que te guste.
6. Revisa que todas tus etiquetas abran y cierren correctamente.
