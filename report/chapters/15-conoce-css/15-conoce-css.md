# Lección 5: Conoce a CSS

## Video de la Clase
*Enlace al video de YouTube:* [Añadir enlace aquí]

## Entorno de Práctica
*Empieza a programar de inmediato (¡Sin instalar nada!):*
- **[Abrir Replit - Bucle infinito](https://codepen.io/pen)**
- **[Abrir JDoodle - Bucle infinito](https://codepen.io/pen)**

## Transcripción / Notas de la Clase

¡Hola de nuevo, creadores! Hasta ahora, hemos construido un excelente esqueleto para nuestra aplicación usando HTML. Sin embargo, no tiene mucho estilo. ¡Es hora de pintar y decorar nuestra casa! Hoy vamos a conocer oficialmente a CSS (*Hojas de Estilo en Cascada*).

**La Regla CSS, las Llaves y sus Componentes**
A diferencia de HTML, en CSS no usamos etiquetas con `< >`. Usamos algo llamado "reglas" para decirle a la computadora a quién queremos pintar y cómo:
- **El Selector:** Es a quién llamamos. Si queremos pintar el fondo de toda la página, le decimos: ¡Oye, `body`! Ven para acá.
- **Las Llaves `{ }`:** Todo lo que escribamos dentro de ellas será la lista de instrucciones de diseño exclusivamente para ese elemento.
- **Propiedades y Valores:** Las instrucciones se dividen en dos: la propiedad (qué queremos cambiar) y el valor (cómo queremos que se vea). Por ejemplo: `background-color: lightblue;`. ¡Y nota crítica! Siempre terminamos la instrucción con un punto y coma `;`.

Si hacemos lo mismo con el título llamando al selector `h1`, abriendo llaves y usando la propiedad `color: darkblue;`, nuestro título principal ahora cobra vida.

**Tipos de Selectores Básicos**
No siempre queremos pintar toda la página o todos los títulos. CSS tiene tres formas de seleccionar elementos:
- **Etiqueta (ej. `body`, `h1`):** Sirve para estilos generales. Busca todas las etiquetas con ese nombre en la página.
- **Clase (ej. `.destacado`):** Se usa con un punto al inicio. Sirve para reutilizar estilos en diferentes elementos. En HTML se escribe como `class="destacado"`.
- **ID (ej. `#principal`):** Se usa con un numeral. Sirve para un elemento único y muy específico. En HTML se escribe como `id="principal"`.

> **Mini ejemplo de clase:** Si tienes varios párrafos pero solo quieres destacar uno, le agregas `class="importante"` en HTML. Luego en CSS escribes `.importante { color: red; }`. Así el navegador cambia únicamente ese párrafo especial.

**Colores, Contraste y Buenas Prácticas**
Llevar el diseño a la práctica requiere cuidar la legibilidad y evitar errores comunes de escritura:
- **Establecer Colores:** CSS acepta nombres en inglés (`red`, `pink`, `lightgreen`) y códigos hexadecimales exactos (`#fce4ec`).
- **Contraste y Legibilidad:** Un buen diseño se debe entender sin esfuerzo. Si el fondo es muy claro y el texto también, costará leerlo. Busca siempre un buen contraste.
- **Errores Comunes:** Si tu CSS no funciona, revisa la puntuación. ¿Te faltaron los dos puntos `:`, el punto y coma `;` o cerrar una llave `{ }`? El navegador los necesita sí o sí.

**Formas de escribir CSS**
Para cerrar, recuerda que hay tres maneras de añadir estilos, pero no debemos abusar de ellas:
1. **Panel / Archivo CSS:** Es la forma más ordenada. Mantiene el HTML por un lado y el diseño por otro (la que usaremos en el curso).
2. **Etiqueta `<style>` en el `<head>`:** Funciona para ejemplos pequeños, pero se desorganiza rápido si la página crece.
3. **Atributo `style` (Inline):** Se escribe directo dentro de la etiqueta HTML. Es rápido para probar, pero mezcla contenido con diseño y hace difícil mantener el código.

## Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
```html
<html lang="es">
  <body>
    <h1>Mi primera web con estilo</h1>
    <p>Estoy aprendiendo a separar la estructura del diseño. Es genial ver cómo cambia de color.</p>
  </body>
</html>

```
**CSS:**
```css
/* Escribe aquí tu primera regla para el 'body' */
/* Escribe aquí tu regla para el título 'h1' */
```

## Código Final (Solution)

**HTML:**
```html
  <html lang="es">
    <body>
      <h1>Mi primera web con estilo</h1>
      <p>Estoy aprendiendo a separar la estructura del diseño. Es genial ver cómo cambia de color.</p>
    </body>
  </html>
```

**CSS:**
```css
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
```

## Actividad Práctica
**Reto (6 minutos): ¡Pinta tu aplicación!**
1. En el panel de CSS, crea un selector para el ody.
2. Dentro de las llaves { }, utiliza la propiedad ackground-color y escribe un color en inglés (yellow, lightgreen, coral, etc.). No olvides cerrar con ;.
3. Crea un nuevo selector, pero esta vez para el h1 (el título). 
4. Usa la propiedad color y asígnale un color que haga contraste con el fondo.
5. (Extra): Intenta crear un tercer selector para el <p> (párrafo) y ponle un color distinto. ¡Revisa que no falte ningún punto y coma!

## Referencias y Bibliografía
- **MDN Web Docs:** [CSS basics / Conceptos básicos de CSS](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics)
- **W3C HTML & CSS:** [Learning CSS / Aprendiendo CSS](https://www.w3.org/standards/webdesign/htmlcss)