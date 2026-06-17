# Lección 2: El esqueleto de tu página

## 1. Ficha Técnica
- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Identificar y redactar la estructura básica de un documento HTML (`<html>`, `<head>`, `<body>`), comprendiendo el concepto de etiquetas anidadas y atributos.

## 2. Conceptos Clave

### 2.1. Estructura de un documento HTML

Un documento HTML se construye con etiquetas anidadas: unas se abren y otras se cierran dentro de ellas.

![Etiquetas anidadas: visualización de cómo las etiquetas HTML se abren y cierran dentro de otras.](report/assets/lesson-02/etiquetas-anidadas.png)

- La etiqueta `<html lang="es">` envuelve toda la página y le indica al navegador que el contenido está en español.
- La etiqueta `<head>` guarda información para el navegador, como el título de la pestaña.
- La etiqueta `<body>` contiene todo lo que el visitante ve en pantalla.

![Estructura general de un documento HTML: relación entre las etiquetas html, head y body.](report/assets/lesson-02/estructura-html.png)

### 2.2. ¿Qué ve el usuario vs. qué ve el navegador?

No todo el código HTML se muestra en la página. El `<head>` contiene información invisible para el visitante pero esencial para el navegador.

![Anatomía del navegador: el título de la pestaña proviene del head, mientras que el contenido visible viene del body.](report/assets/lesson-02/anatomia-navegador.png)

### 2.3. CodePen

**CodePen** divide la pantalla en HTML, CSS y Resultado.

### 2.4. Indentación

La indentación no cambia lo que se muestra, pero ayuda a leer y entender mejor la estructura.

![Indentación correcta vs incorrecta: comparación de código bien organizado con código difícil de leer.](report/assets/lesson-02/identacion-correcta-incorrecta.png)

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen (proporcionar enlace al alumno)*

Los archivos de inicio para esta lección están disponibles en la carpeta [/starter-files/lesson-02](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-02/):
- HTML base: [index.html](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-02/index.html)
- CSS base: [styles.css](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-02/styles.css)

**HTML:**
```html
<!-- Escribe aquí tu estructura básica HTML -->

```

**CSS:**
```css
/* Hoy no usaremos CSS, ¡solo estructura! */
```

## 4. Código Final (Solution)

El código de la solución completada está disponible en la carpeta [/completed-examples/lesson-02](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-02/):
- HTML completo: [index.html](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-02/index.html)
- CSS completo: [styles.css](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-02/styles.css)

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

## 5. Actividad Práctica

**Reto (5 minutos): ¡Arma el Esqueleto!**
1. Abre el CodePen de inicio. En el panel **HTML** verás un comentario de ayuda; en el panel **CSS** no escribirás nada todavía.
2. Reemplaza el comentario del panel **HTML** por la estructura completa del documento.
3. Escribe la etiqueta principal `<html lang="es">` y cierra el documento con `</html>` al final.
4. Dentro de `<html>`, crea primero `<head>` y luego `<body>`, respetando el orden y la sangría.
5. Dentro de `<head>`, añade un `<title>` con el nombre de tu página, por ejemplo: `La web de mis hobbies`.
6. Dentro de `<body>`, agrega un `<h1>` para dar la bienvenida y un `<p>` con un pasatiempo que te guste.
7. Revisa que todas las etiquetas de apertura tengan su cierre y que quede claro qué elemento está dentro de cuál.
