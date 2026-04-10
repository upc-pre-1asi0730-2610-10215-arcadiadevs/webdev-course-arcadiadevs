# Lección 4: Multimedia y navegación

## 1. Ficha Técnica
- **Duración estimada:** 8 minutos.
- **Objetivo de aprendizaje:** Enriquecer la aplicación web insertando imágenes mediante la etiqueta <img> y creando enlaces hipertexto con la etiqueta <a>, comprendiendo el uso de los atributos src, lt y href.

## 2. Guion de Video

**[Escena 1: Más allá del texto]**
- *(Visual: El instructor sonríe. Se muestra una página web con puro texto y luego se transforma en una con imágenes y botones brillantes).*
- **Instructor (Audio):** "¡Hola! Hasta ahora nuestra página tiene mucha información valiosa, pero admitámoslo, ¡el texto solo puede ser un poco aburrido! Es hora de añadir colores, caras y destinos. Es hora de aprender a insertar imágenes y enlaces."

**[Escena 2: Insertando la primera imagen]**
- *(Visual: Pantalla de CodePen. El instructor escribe la etiqueta <img>).*
- **Instructor (Audio):** "Para agregar una foto usamos la etiqueta <img>. Pero aquí viene el truco: esta etiqueta no necesita cerrarse como las demás, ¡trabaja sola! Lo que sí necesita es un atributo esencial llamado src (que significa fuente). Ahí colocamos la dirección web de nuestra imagen. Vamos a obtener una foto de un perrito desde una biblioteca gratuita de imágenes en internet."
- *(Visual: Completa el código con <img src="URL_DEL_PERRITO"> y la imagen aparece).*

**[Escena 3: El atributo de accesibilidad (alt)]**
- *(Visual: Zoom al código, añadiendo el atributo lt).*
- **Instructor (Audio):** "Un requisito muy importante para ser buenos desarrolladores es pensar en todos. Si la imagen no carga por alguna razón, o si una persona con discapacidad visual visita nuestra página, usamos el atributo lt (texto alternativo) para describir qué hay en la foto."
- *(Visual: Añade lt="Un perrito feliz saltando").*

**[Escena 4: Viajando por internet (Enlaces)]**
- *(Visual: El instructor dibuja una flecha mágica en el aire que lo teletransporta a otro escenario).*
- **Instructor (Audio):** "¿Cómo conectamos nuestra página con el resto del mundo? ¡Con enlaces! Utilizamos la etiqueta <a> (de "ancla" en inglés). A esta etiqueta le damos el atributo href, donde declaramos hacia dónde queremos viajar al hacer clic."

**[Escena 5: Conectando las piezas]**
- *(Visual: Se escribe el código <a href="https://wikipedia.org">Visita Wikipedia</a>).*
- **Instructor (Audio):** "El texto que ponemos entre la apertura y el cierre de la etiqueta <a> será el que aparezca subrayado y en azul. Es como una puerta mágica hacia otra aplicación o página en internet."

**[Escena 6: Cierre y Reto]**
- *(Visual: El instructor anima a la audiencia. Texto: "Reto: Añade tu imagen favorita").*
- **Instructor (Audio):** "¡Nuestra página está cobrando vida! Tu reto de hoy será poner la foto de algo que te guste y un enlace para que los visitantes conozcan más de ti. ¡A darle al código!"

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<html lang="es">
  <head>
    <title>Multimedia y Enlaces</title>
  </head>
  <body>
    <h1>Mis cosas favoritas</h1>
    
    <!-- Añade tu imagen debajo de esta línea -->
    
    
    <!-- Añade tu propio enlace aquí -->
    
  </body>
</html>
`

**CSS:**
`css
/* Continuamos sin CSS, ¡ya casi llegamos a esa parte! */
`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <head>
    <title>Multimedia y Enlaces</title>
  </head>
  <body>
    <h1>Mis cosas favoritas</h1>
    
    <h2>Mi mascota ideal</h2>
    <!-- Imagen con sus atributos src y alt -->
    <img src="https://images.unsplash.com/photo-1543852786-1cf6624b9987" alt="Un gato asomándose curioso">
    
    <h2>Mi lugar favorito</h2>
    <!-- Enlace hacia otra página -->
    <p>Me gustaría viajar al espacio. Puedes aprender más en la <a href="https://www.nasa.gov/">página de la NASA</a>.</p>
  </body>
</html>
`

**CSS:**
`css
/* Seguimos concentrados en HTML */
`

## 5. Actividad Práctica

**Reto (5 minutos): ¡Agrega tu esencia visual!**
1. En tu CodePen, busca una imagen que te guste (puedes buscar en Google Imágenes, hacer clic derecho sobre la foto y elegir "Copiar dirección de la imagen").
2. Usa la etiqueta <img> con el atributo src para pegar esa dirección. ¡Asegúrate de ponerlo entre comillas!
3. Añade el atributo lt y describe tu imagen con palabras.
4. Crea un enlace usando la etiqueta <a> e inserta el atributo href con la dirección de tu página, videojuego o red social favorita.
5. Haz clic en el enlace para asegurarte de que te lleva al lugar correcto.
