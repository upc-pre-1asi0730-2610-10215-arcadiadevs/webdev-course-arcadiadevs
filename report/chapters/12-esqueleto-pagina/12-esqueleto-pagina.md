# Lección 2: El esqueleto de tu página

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Identificar y redactar la estructura básica de un documento HTML (`<html>`, `<head>`, `<body>`), comprendiendo el concepto de etiquetas anidadas y atributos.

## 2. Conceptos Clave
- **CodePen** divide la pantalla en HTML, CSS y Resultado.
- Un documento HTML se construye con etiquetas anidadas: unas se abren y otras se cierran dentro de ellas.
- La etiqueta `<html lang="es">` envuelve toda la página y le indica al navegador que el contenido está en español.
- La etiqueta `<head>` guarda información para el navegador, como el título de la pestaña.
- La etiqueta `<body>` contiene todo lo que el visitante ve en pantalla.
- La indentación no cambia lo que se muestra, pero ayuda a leer y entender mejor la estructura.

## 3. Guion de Video

**[Escena 1: Introducción al Esqueleto Humano]**
- *(Visual: El instructor saluda. Aparece la silueta de una persona dividida en cabeza y cuerpo).*
- **Instructor (Audio):** "¡Hola de nuevo! En la lección anterior vimos cómo mostrar contenido y darle estilo. Ahora vamos a construir la base de la página para que el navegador entienda dónde empieza todo, dónde va la información de apoyo y qué parte verá el usuario."

**[Escena 2: La Etiqueta Principal]**
- *(Visual: Pantalla de CodePen vacía. El instructor empieza a escribir `<html lang="es">` y `</html>`).*
- **Instructor (Audio):** "Todo empieza con la etiqueta `<html>`. Esta etiqueta envuelve a toda la página. Dentro de la etiqueta de apertura podemos añadir un atributo, como `lang="es"`, para decirle al navegador que el contenido está en español."

**[Escena 3: La Cabeza (El cerebro de la página)]**
- *(Visual: Se escribe la etiqueta `<head>` dentro de `<html>`).*
- **Instructor (Audio):** "Dentro de `<html>`, tenemos la etiqueta `<head>`. Aquí colocamos información importante para el navegador que normalmente no se ve en la página, como el texto que aparece en la pestaña. Ese texto lo escribimos con la etiqueta `<title>`."

**[Escena 4: El Cuerpo (Lo que todos ven)]**
- *(Visual: Se escribe la etiqueta `<body>` debajo de `<head>`. Se añade un `<h1>` y un `<p>`).*
- **Instructor (Audio):** "Luego viene `<body>`, el cuerpo. Aquí colocamos todo lo que queremos que el visitante vea: títulos, párrafos, imágenes y más. Escribamos un título y un pequeño párrafo dentro de esta sección."

**[Escena 5: Repaso del Código y Visualización]**
- *(Visual: Se muestra el código completo bien ordenado (indentado). Una flecha señala cómo las etiquetas se abren y se cierran).*
- **Instructor (Audio):** "Fíjate cómo las etiquetas se abren y se cierran con una barra inclinada `/`. Es como abrir una caja, poner contenido dentro y luego cerrarla. La indentación nos ayuda a ver qué va dentro de qué, aunque lo más importante es que las etiquetas estén bien anidadas."

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor en cámara sonriendo. Texto: "Reto: Construye tu esqueleto").*
- **Instructor (Audio):** "¡Gran trabajo! Ahora ya conoces la anatomía básica de una página web. En la sección práctica vas a construir este esqueleto desde cero. Inténtalo con calma y revisa que cada etiqueta tenga su pareja."

## 4. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
```html
<!-- Escribe aquí tu estructura básica HTML -->

```

**CSS:**
```css
/* Hoy no usaremos CSS, ¡solo estructura! */
```

## 5. Código Final (Solution)

**HTML:**
```html
<html lang="es">
  <head>
    <title>La web de mis hobbies</title>
  </head>
  <body>
    <h1>¡Bienvenidos a mi primera web formal!</h1>
    <p>Me encanta aprender desarrollo web. Este es el cuerpo de mi página.</p>
  </body>
</html>
```

**CSS:**
```css
/* Vacío por ahora */
```

## 6. Actividad Práctica

**Reto (5 minutos): ¡Arma el Esqueleto!**
1. Abre el CodePen de inicio. En el panel **HTML** verás un comentario de ayuda; en el panel **CSS** no escribirás nada todavía.
2. Reemplaza el comentario del panel **HTML** por la estructura completa del documento.
3. Escribe la etiqueta principal `<html lang="es">` y cierra el documento con `</html>` al final.
4. Dentro de `<html>`, crea primero `<head>` y luego `<body>`, respetando el orden y la sangría.
5. Dentro de `<head>`, añade un `<title>` con el nombre de tu página, por ejemplo: `La web de mis hobbies`.
6. Dentro de `<body>`, agrega un `<h1>` para dar la bienvenida y un `<p>` con un pasatiempo que te guste.
7. Revisa que todas las etiquetas de apertura tengan su cierre y que quede claro qué elemento está dentro de cuál.
