# Lección 3: Organizando la información

## 1. Ficha Técnica
- **Duración estimada:** 8 minutos.
- **Objetivo de aprendizaje:** Estructurar contenido de forma clara y jerárquica utilizando encabezados (<h1> a <h6>), párrafos (<p>) y listas (<ul>, <ol>, <li>), para facilitar la lectura de la información en una aplicación web.

## 2. Guion de Video

**[Escena 1: Introducción a la Organización]**
- *(Visual: El instructor saluda. En pantalla aparece un bloque de texto inmenso y sin formato, muy difícil de leer).*
- **Instructor (Audio):** "¡Hola! Imagina leer un libro que no tiene títulos, capítulos ni separación entre párrafos. Sería muy difícil de entender, ¿verdad? Lo mismo pasa en las páginas web. Hoy aprenderemos a organizar nuestra información para que todos puedan leerla fácilmente."

**[Escena 2: Los Encabezados (Jerarquía)]**
- *(Visual: Transición a la pantalla de CodePen. Se muestra el código base con el <body>).*
- **Instructor (Audio):** "Para crear títulos, usamos las etiquetas <h1> hasta <h6>. El <h1> es el título principal, el más grande, y solo debe haber uno por página. Los <h2> y <h3> son como subtítulos. ¡Escribamos un <h2> para presentar nuestros pasatiempos!"
- *(Visual: Escribe <h2>Mis Pasatiempos Favoritos</h2> y se muestra el resultado).*

**[Escena 3: Escribiendo Párrafos]**
- *(Visual: Se escribe una etiqueta <p> debajo del <h2>).*
- **Instructor (Audio):** "Cuando queremos escribir una pequeña historia o descripción, usamos la etiqueta <p>, de párrafo. Todo el texto que pongas dentro quedará agrupado y será muy fácil de leer para nuestros visitantes."
- *(Visual: Escribe <p>Me encanta pasar el tiempo aprendiendo cosas nuevas y creando mis propios proyectos.</p>).*

**[Escena 4: Las Listas (Ordenadas y Desordenadas)]**
- *(Visual: Se muestran dos cajas, una con viñetas (puntos) y otra con números).*
- **Instructor (Audio):** "¿Y si queremos hacer una lista? ¡Tenemos dos opciones! Si el orden no importa, como una lista de compras, usamos <ul> (Unordered List) y colocamos viñetas. Si el orden es clave, como los pasos de un tutorial, usamos <ol> (Ordered List) que nos dará números. Vamos a crear una lista <ul> con nuestras películas favoritas."

**[Escena 5: Elementos de la Lista]**
- *(Visual: Escribe la etiqueta <ul> y dentro varias etiquetas <li>).*
- **Instructor (Audio):** "Ojo aquí: dentro de cualquiera de las dos listas (<ul> o <ol>), cada uno de los elementos siempre se escribe usando la etiqueta <li> (List Item). Mira cómo se añaden automáticamente los puntitos en pantalla."
- *(Visual: El instructor añade 3 elementos <li> a la lista).*

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor en pantalla completa. Texto: "Reto: ¡Haz tu lista de metas!").*
- **Instructor (Audio):** "¡Genial! Hemos logrado darle orden a nuestra información, un requisito indispensable para crear cualquier aplicación web moderna. Ahora, en nuestro reto, crearás tu propia lista personal. ¡A codificar y nos vemos en el próximo video!"

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<html lang="es">
  <head>
    <title>Perfil de [Tu Nombre]</title>
  </head>
  <body>
    <!-- Escribe aquí debajo un título secundario -->
    
    <!-- Escribe aquí un párrafo sobre ti -->
    
    <!-- Crea tu lista aquí abajo -->
    
  </body>
</html>
`

**CSS:**
`css
/* Hoy tampoco usamos estilos, ¡concéntrate en la organización! */
`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <head>
    <title>Perfil de Estudiante</title>
  </head>
  <body>
    <!-- Encabezado secundario -->
    <h2>Mis Películas Favoritas</h2>
    
    <!-- Párrafo -->
    <p>Me gusta mucho el cine de ciencia ficción y los documentales del espacio.</p>
    
    <!-- Lista desordenada con viñetas -->
    <ul>
      <li>Interstellar</li>
      <li>Matrix</li>
      <li>Volver al Futuro</li>
    </ul>

    <!-- Lista ordenada con números (extra) -->
    <h3>Mis próximos aprendizajes:</h3>
    <ol>
      <li>HTML avanzado</li>
      <li>Programar con CSS</li>
      <li>Crear una aplicación web completa</li>
    </ol>
  </body>
</html>
`

**CSS:**
`css
/* Vacío por ahora */
`

## 5. Actividad Práctica

**Reto (4 minutos): ¡Organiza tus intereses!**
1. Abre tu plantilla en CodePen.
2. Añade un título secundario (<h2>) que diga "Cosas que quiero aprender este año".
3. Escribe un párrafo (<p>) explicando por qué quieres aprender esas cosas.
4. Usa una lista ordenada (<ol>) y adentro escribe al menos 3 metas para este año usando la etiqueta <li>. ¡Observa cómo CodePen le asigna los números automáticamente!
5. Verifica que ninguna de tus etiquetas se haya quedado sin cerrar.
