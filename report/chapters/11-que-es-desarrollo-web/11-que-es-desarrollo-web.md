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

## 3. Guion de Video

**[Escena 1: Introducción]**
- *(Visual: El instructor sonríe a la cámara. Texto en pantalla: "¡Crea tu propia web en minutos!")*
- **Instructor (Audio):** "¡Hola! ¿Alguna vez te has preguntado cómo se construyen las páginas web que visitas todos los días? Hoy vas a descubrirlo y, lo mejor de todo, ¡escribirás tu propio código en los próximos 5 minutos! No necesitas instalar ninguna aplicación, todo lo haremos desde el navegador."

**[Escena 2: La Analogía del Edificio]**
- *(Visual: Animación gráfica o dibujo en pantalla. Aparece el esqueleto de una casa de ladrillos, luego se pinta y decora).*
- **Instructor (Audio):** "Imagina que una página web es como una casa. El **HTML** son los ladrillos, las paredes y el techo. Es el esqueleto que le da estructura a nuestra información. Por otro lado, el **CSS** es la pintura, los muebles y la decoración. Es lo que hace que nuestra casa (o página web) se vea increíble."

**[Escena 3: Entorno de Trabajo (CodePen)]**
- *(Visual: Grabación de pantalla mostrando la interfaz de CodePen. Resaltar en rojo los paneles de HTML, CSS y Resultado).*
- **Instructor (Audio):** "Para empezar, usaremos una plataforma increíble llamada CodePen. Es una herramienta 100% online donde escribimos código y vemos el resultado al instante. HTML nos dice qué contenido debe aparecer, CSS nos dice cómo se ve y el navegador combina ambos para mostrarnos la página en el área de Resultado."

**[Escena 4: Manos a la Obra]**
- *(Visual: Escribiendo en el panel de HTML. Un zoom suave al texto).*
  ```html
  <h1>Hola Mundo</h1>
  ```
- **Instructor (Audio):** "Vamos a escribir nuestro primer código HTML. Piensa en esto como decirle al navegador qué contenido debe colocar en la página. No hace falta memorizar nada todavía; solo observa cómo el texto aparece en el resultado de inmediato. Pero se ve un poco aburrido, ¿verdad? Vamos a darle vida."

**[Escena 5: Agregando Estilos]**
- *(Visual: Escribiendo en el panel de CSS. Resaltar la propiedad color).*
- **Instructor (Audio):** "Ahora vamos al panel de CSS. Aquí no cambiamos el contenido, solo la apariencia. Escribimos la regla dentro de las llaves del selector `h1`, así: `h1 { color: blue; }`. El navegador toma esa instrucción, la aplica al título y lo pinta de azul. El texto sigue siendo el mismo, pero ahora se ve diferente. Con solo dos líneas de código, ya has empezado tu viaje en el desarrollo web."

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor en cámara apuntando a la pantalla. Texto: "Reto: ¡Tu turno!").*
- **Instructor (Audio):** "Ahora te toca a ti. Usa el código de inicio que te hemos dejado y completa la misión de la actividad práctica. ¡Nos vemos en la próxima lección donde construiremos el esqueleto completo de tu primera página!"

## 4. Código de Inicio (Starter Code)

*Plataforma: CodePen (proporcionar enlace al alumno)*

**HTML:**
```html
<h1>Hola Mundo</h1>
```

**CSS:**
```css
/* Aquí escribiremos nuestros estilos */
```

## 5. Código Final (Solution)

**HTML:**
```html
<h1>Hola Mundo</h1>
```

**CSS:**
```css
h1 {
  color: blue;
}
```

## 6. Actividad Práctica

**Reto (3 minutos): ¡Hazlo tuyo!**
1. Abre el CodePen con el Código de Inicio. Debes ver tres zonas: **HTML**, **CSS** y **Resultado**.
2. En el panel **HTML**, cambia solo el texto que está entre las etiquetas `<h1>` y `</h1>` para que diga `¡Hola, soy [Tu Nombre]!`.
3. No borres la etiqueta `<h1>` ni la etiqueta de cierre `</h1>`; solo reemplaza el texto del medio por tu nombre o el nombre que quieras mostrar.
4. En el panel **CSS**, deja el selector `h1` tal como está y cambia únicamente `blue` por un color en inglés, por ejemplo: `red`, `green`, `purple` u `orange`.
5. Verifica que en **Resultado** aparezca el mismo texto, pero ahora con tu nombre y el color que elegiste.
6. Si no ves cambios, revisa que no hayas quitado el punto y coma `;` ni las llaves `{ }`.
