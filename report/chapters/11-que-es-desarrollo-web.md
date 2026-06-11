# Lección 1: ¿Qué es el desarrollo web?

## 1. Ficha Técnica
- **Duración estimada:** 5 minutos.
- **Objetivo de aprendizaje:** Comprender el concepto básico de desarrollo web y diferenciar claramente el rol de HTML (estructura) y CSS (estilos), utilizando CodePen.

## 2. Conceptos Clave

### 2.1. Las Herramientas Básicas
- **CodePen**: Es un entorno de desarrollo en línea que divide la pantalla en tres zonas: edición de HTML, edición de CSS y la vista previa del Resultado en vivo.

![Entorno de trabajo en CodePen, dividido en paneles para HTML, CSS y la vista de Resultado en vivo.](report/assets/lesson-01/codepen.png)

- **HTML (HyperText Markup Language)**: Define qué contenido existe en la página (textos, títulos, imágenes) y el orden en el que aparecen. Es el "esqueleto" o los "ladrillos" de nuestra web.
- **CSS (Cascading Style Sheets)**: Define cómo se presenta visualmente ese contenido (colores, tamaños, fuentes, márgenes). Es la "pintura" y la "decoración".

![Analogía de la casa: HTML representa la estructura o esqueleto y CSS representa los acabados, pintura y estilos visuales.](report/assets/lesson-01/casa-esqueleto-presentacion.png)

- **El Navegador**: Su función es leer primero el documento HTML para crear el contenido, luego leer y aplicar las reglas del CSS, y finalmente renderizar el resultado final en la pantalla.

![Procesamiento del navegador: combinación de archivos HTML y CSS para renderizar la página web final.](report/assets/lesson-01/procesamiento-navegador.png)

### 2.2. ¿Por qué separamos el Contenido (HTML) del Estilo (CSS)?
Dividir el desarrollo web en estas dos tecnologías separadas es una de las mejores prácticas de la industria:
1. **Mantenimiento sencillo**: Si necesitas modificar la información o el texto de tu página web, solo editas el archivo HTML sin alterar su diseño. Si decides cambiar el color o tamaño de los títulos de todo tu sitio web, solo editas una regla en tu hoja de estilos CSS sin tocar la información escrita.
2. **Reutilización**: Un único archivo CSS de estilos se puede enlazar a decenas de páginas HTML diferentes, dándoles a todas un aspecto coherente y corporativo al instante.

### 2.3. ¿Por qué usamos los nombres `index.html` y `styles.css`?
Al estructurar nuestro proyecto en carpetas locales, verás que usamos nombres muy específicos por convención:
- **`index.html`**: Es el nombre estándar reservado para la página de inicio o portada de un sitio web. Cuando un servidor web recibe una petición para entrar a una carpeta (por ejemplo, `misitio.com/`), busca de forma automática un archivo llamado `index.html` para mostrarlo por defecto. Si tuviera otro nombre, el navegador podría mostrar una lista vacía de archivos o un error de acceso.
- **`styles.css`**: Es la convención más común para nombrar el archivo principal de estilos. Permite a cualquier programador que lea nuestro proyecto identificar inmediatamente dónde se encuentra toda la lógica visual de la página.

### 2.4. Consejos y Errores Comunes
- **Cierre de etiquetas**: Las etiquetas de HTML suelen trabajar en parejas: una de apertura (`<h1>`) y otra de cierre (`</h1>`). Si olvidas cerrar una etiqueta, el navegador podría desconfigurar todo el contenido restante intentando aplicar el mismo formato.
- **Sintaxis en CSS**: Las instrucciones en CSS se agrupan entre llaves `{ }` y cada propiedad debe finalizar con un punto y coma `;` (por ejemplo, `color: blue;`). Olvidar el `;` al final de una línea es el error más frecuente y hace que el navegador ignore esa regla y las siguientes.

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

![Anatomía de una regla CSS: desglose de selector, propiedad, valor, llaves y punto y coma.](report/assets/lesson-01/anatomia-css.png)

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