# Lección 6: Tipografía y estilo

## 1. Ficha Técnica
- **Duración estimada:** 8 minutos.
- **Objetivo de aprendizaje:** Identificar cómo manipular la tipografía (ont-family, ont-size) y comprender la jerarquía visual para asegurar que las aplicaciones web mantengan un diseño legible y minimalista.

## 2. Guion de Video

**[Escena 1: El poder de las letras]**
- *(Visual: El instructor compara el mismo texto escrito con letra cursiva elegante vs una letra de molde descuidada).*
- **Instructor (Audio):** "¡Hola de nuevo! Imagina que lees una solicitud formal escrita con letras de cómic; nadie te tomaría en serio. La letra, o 'tipografía', comunica emociones. Hoy le pondremos personalidad a nuestra página cambiando sus fuentes y tamaños."

**[Escena 2: Cambiando la Fuente (font-family)]**
- *(Visual: Interfaz de CodePen. Resaltando el texto del ody en el panel de CSS).*
- **Instructor (Audio):** "Para cambiar el tipo de letra, usamos la propiedad ont-family. Veamos cómo cambia nuestro texto principal si le damos un estilo limpio y sin adornos conocido como *sans-serif*, por ejemplo, 'Arial' o 'Helvetica'. Escribiremos: ont-family: Arial, sans-serif;."

**[Escena 3: Traer fuentes de internet (Google Fonts en CodePen)]**
- *(Visual: Transición rápida mostrando el panel de configuraciones en CodePen > CSS > 'Add External Stylesheet' o usando @import visual).*
- **Instructor (Audio):** "¿Quieres fuentes más increíbles? Hay una biblioteca enorme y gratuita llamada Google Fonts. Si encuentras una fuente genial, como 'Roboto' o 'Pacifico', puedes importarla a tu proyecto. Para mantenerlo simple, usaremos fuentes que ya vienen en todos los navegadores, pero ten en mente que internet está lleno de opciones de fuentes para obtener e instalar."

**[Escena 4: Tamaños y Jerarquía visual]**
- *(Visual: Un título muy pequeño compitiendo contra un texto gigante. Una equis roja aparece de "error").*
- **Instructor (Audio):** "Un requisito para un buen diseño es guiar los ojos del visitante. A esto le decimos *jerarquía visual*. Lo más importante debe ser lo más grande. Vamos a usar la propiedad ont-size para darle a nuestro título h1 un tamaño de 40px (píxeles), y a nuestro párrafo un tamaño base de 18px, para que se lea fácil."

**[Escena 5: Alineando Sentimientos (text-align)]**
- *(Visual: El título principal se desliza suavemente al centro de la página).*
- **Instructor (Audio):** "Para rematar nuestra lección, a veces queremos que los títulos estén centrados. Con tan solo agregar 	ext-align: center; en la regla de nuestro h1, observa cómo el título se posiciona en medio de la pantalla."

**[Escena 6: Cierre y Reto]**
- *(Visual: Instructor empoderado. Texto en pantalla: "Reto: ¡Personaliza tu lectura!").*
- **Instructor (Audio):** "Acomodar tu texto marca la diferencia entre un diseño novato y uno profesional. Con el código inicial, juega con el tamaño y el estilo. Haz que nuestra aplicación se vea limpia y atractiva. ¡Nos vemos!"

## 3. Código de Inicio (Starter Code)

*Plataforma: CodePen*

**HTML:**
`html
<html lang="es">
  <body>
    <h1>Bienvenido a mi mundo</h1>
    <p>Este es mi primer diseño con jerarquía visual y tipografías geniales.</p>
  </body>
</html>
`

**CSS:**
`css
/* Modifica tu body y tu título aquí */
body {
  background-color: #f7f9fc;
  /* Añade font-family aquí */
  
}

h1 {
  color: #2c3e50;
  /* Centra este título y aumenta su tamaño a 40px */
  
}

p {
  color: #34495e;
  /* Pon el tamaño de este párrafo a 18px */
  
}
`

## 4. Código Final (Solution)

**HTML:**
`html
<html lang="es">
  <body>
    <h1>Bienvenido a mi mundo</h1>
    <p>Este es mi primer diseño con jerarquía visual y tipografías geniales.</p>
  </body>
</html>
`

**CSS:**
`css
body {
  background-color: #f7f9fc;
  /* Se agrega tipografía limpia */
  font-family: "Verdana", sans-serif;
}

h1 {
  color: #2c3e50;
  /* Centrando y dando tamaño al protagonista */
  font-size: 40px;
  text-align: center;
}

p {
  color: #34495e;
  /* Legibilidad cómoda */
  font-size: 18px;
}
`

## 5. Actividad Práctica

**Reto (4 minutos): ¡Haz que se lea bien!**
1. En CSS, dentro de tu regla ody, agrega la propiedad ont-family y asígnale el valor Verdana, sans-serif;. Observa cómo cambian las letras al instante.
2. Ve a la regla de tu h1. Aumenta su tamaño dándole a la propiedad ont-size un valor de 40px;.
3. Haz que tu título sea el centro de atención añadiéndole 	ext-align: center;.
4. Finalmente, haz que el párrafo <p> se lea grande y claro. Ponle un ont-size de 18px; o 20px;.
