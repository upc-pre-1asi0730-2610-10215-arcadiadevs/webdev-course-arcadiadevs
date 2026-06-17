# Lección 2: El esqueleto de tu página

_(Contenido para los instructores)_

## 1. Estructura de Carpetas (GitHub)

```text
/starter-files/lesson-02        # Carpeta con el codigo base para la clase
├── index.html
└── styles.css
/completed-examples/lesson-02   # El código completo de la lección
├── index.html
└── styles.css
```

## 2. Ficha Técnica

- **Duración estimada:** 7 minutos.
- **Objetivo de aprendizaje:** Identificar y redactar la estructura básica de un documento HTML (`<html>`, `<head>`, `<body>`), comprendiendo el concepto de etiquetas anidadas y atributos.

## 3. Guion de Video (8 minutos)

> **[Escena 1: Introducción al Esqueleto Humano]**
> - **Visual:** Pantalla de apertura con la silueta de una persona dividida en cabeza y cuerpo.
> - **Voz en off (Audio):** "¡Hola de nuevo! En la lección anterior vimos cómo mostrar contenido y darle estilo. Ahora vamos a construir la base de la página para que el navegador entienda dónde empieza todo, dónde va la información de apoyo y qué parte verá el usuario."
>
> **[Escena 2: La Etiqueta Principal]**
> - **Visual:** Pantalla de CodePen vacía. Se escribe `<html lang="es">` y `</html>`.
> - **Voz en off (Audio):** "Todo empieza con la etiqueta `<html>`. Esta etiqueta envuelve a toda la página. Dentro de la etiqueta de apertura podemos añadir un atributo, como `lang="es"`, para decirle al navegador que el contenido está en español."
>
> **[Escena 3: La Cabeza (El cerebro de la página)]**
> - **Visual:** Se escribe la etiqueta `<head>` dentro de `<html>`.
> - **Voz en off (Audio):** "Dentro de `<html>`, tenemos la etiqueta `<head>`. Aquí colocamos información importante para el navegador que normalmente no se ve en la página, como el texto que aparece en la pestaña. Ese texto lo escribimos con la etiqueta `<title>`."
>
> **[Escena 4: El Cuerpo (Lo que todos ven)]**
> - **Visual:** Se escribe la etiqueta `<body>` debajo de `<head>`. Se añade un `<h1>` y un `<p>`.
> - **Voz en off (Audio):** "Luego viene `<body>`, el cuerpo. Aquí colocamos todo lo que queremos que el visitante vea: títulos, párrafos, imágenes y más. Escribamos un título y un pequeño párrafo dentro de esta sección."
>
> **[Escena 5: Repaso del Código y Visualización]**
> - **Visual:** Se muestra el código completo bien ordenado (indentado). Una flecha señala cómo las etiquetas se abren y se cierran.
> - **Voz en off (Audio):** "Fíjate cómo las etiquetas se abren y se cierran con una barra inclinada `/`. Es como abrir una caja, poner contenido dentro y luego cerrarla. La indentación nos ayuda a ver qué va dentro de qué, aunque lo más importante es que las etiquetas estén bien anidadas."
>
> **[Escena 6: Cierre y Reto]**
> - **Visual:** Pantalla de cierre con el texto: "Reto: Construye tu esqueleto" y una vista del editor de CodePen.
> - **Voz en off (Audio):** "¡Gran trabajo! Ahora ya conoces la anatomía básica de una página web. En la sección práctica vas a construir este esqueleto desde cero. Inténtalo con calma y revisa que cada etiqueta tenga su pareja."

## 4. Sugerencias Multimedia

- **Anotaciones en Pantalla:**
  - Mostrar la analogía visual del esqueleto humano: cabeza (`<head>`) vs. cuerpo (`<body>`).
  - Resaltar la estructura de etiquetas anidadas con flechas o recuadros.
- **Resaltado de Sintaxis:**
  - Resaltar en rojo las etiquetas `<html>`, `<head>`, `<body>` y `<title>`.
  - Resaltar el atributo `lang="es"` con un color diferente para distinguirlo de las etiquetas.
- **Transiciones:**
  - Transición suave al pasar de la analogía del esqueleto humano a la estructura HTML.
  - Mostrar una animación de indentación para explicar visualmente el anidamiento de etiquetas.
