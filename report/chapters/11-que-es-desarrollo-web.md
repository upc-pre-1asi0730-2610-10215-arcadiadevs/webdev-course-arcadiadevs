# Lección 1: ¿Qué es el desarrollo web?

## 1. Ficha Técnica
- **Duración estimada:** 5 minutos.
- **Objetivo de aprendizaje:** Comprender el concepto básico de desarrollo web y diferenciar claramente el rol de HTML (estructura) y CSS (estilos), utilizando CodePen.

## 2. Conceptos Clave
- **CodePen** divide la pantalla en tres zonas: HTML, CSS y Resultado.
- **HTML** define qué contenido existe en la página y en qué orden aparece.
- **CSS** define cómo se ve ese contenido: colores, tamaños, espacios y estilos visuales.
- El navegador lee primero el HTML, después aplica el CSS sobre ese mismo contenido y al final muestra el resultado en pantalla.
- En esta clase solo necesitamos entender la idea general; más adelante veremos con más detalle las etiquetas y sus atributos.

## 3. Código de Inicio (Starter Code)
*Plataforma: CodePen (proporcionar enlace al alumno)*

Los archivos de inicio para esta lección están disponibles en la carpeta [/starter-files/lesson-01](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-01/):
- HTML base: [index.html](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-01/index.html)
- CSS base: [styles.css](file:///D:/Projects/webdev-course-arcadiadevs/starter-files/lesson-01/styles.css)

**HTML:**
```html
<h1>Hola Mundo</h1>
<p>Mi primera página</p>
```

**CSS:**
```css
/* Aquí escribiremos nuestros estilos */
```

## 4. Código Final (Solution)
El código de la solución completada está disponible en la carpeta [/completed-examples/lesson-01](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-01/):
- HTML completo: [index.html](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-01/index.html)
- CSS completo: [styles.css](file:///D:/Projects/webdev-course-arcadiadevs/completed-examples/lesson-01/styles.css)

**HTML:**
```html
<h1>Hola Mundo</h1>
<p>Mi primera página</p>
```

**CSS:**
```css
h1 {
  color: blue;
}
```

## 5. Actividad Práctica

**Reto (3 minutos): ¡Hazlo tuyo!**
1. Abre el CodePen con el Código de Inicio. Debes ver tres zonas: **HTML**, **CSS** y **Resultado**.
2. En el panel **HTML**, cambia solo el texto que está entre las etiquetas `<h1>` y `</h1>` para que diga `¡Hola, soy [Tu Nombre]!`.
3. No borres la etiqueta `<h1>` ni la etiqueta de cierre `</h1>`; solo reemplaza el texto del medio por tu nombre o el nombre que quieras mostrar.
4. En el panel **CSS**, deja el selector `h1` tal como está y cambia únicamente `blue` por un color en inglés, por ejemplo: `red`, `green`, `purple` u `orange`.
5. Verifica que en **Resultado** aparezca el mismo texto, pero ahora con tu nombre y el color que elegiste.
6. Si no ves cambios, revisa que no hayas quitado el punto y coma `;` ni las llaves `{ }`.