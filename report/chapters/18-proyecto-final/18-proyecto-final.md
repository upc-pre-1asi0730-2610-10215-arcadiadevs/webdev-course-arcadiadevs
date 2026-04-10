# Lección 8: Proyecto Final y Próximos Pasos

## 1. Ficha Técnica
- **Duración estimada:** 10 minutos.
- **Objetivo de aprendizaje:** Integrar todos los conceptos aprendidos (HTML semántico, enlaces, imágenes, y CSS con Box Model y tipografía) para construir una "Página de Perfil Personal" en Replit y revisar errores sintácticos comunes.

## 2. Guion de Video

**[Escena 1: El Gran Final]**
- *(Visual: El instructor aplaude frente a la cámara. Aparece en pantalla un diploma digital girando).*
- **Instructor (Audio):** "¡Felicidades! Has llegado a la última lección. Has aprendido el esqueleto (HTML), la pintura (CSS), cómo organizar información y dar espacio al diseño. Ahora, tomaremos todo eso para cumplir nuestro requisito final: crear tu primera aplicación web completa, un Perfil Personal en línea."

**[Escena 2: Mudándonos a Replit]**
- *(Visual: Grabación de pantalla mostrando la interfaz de Replit con un archivo index.html y un style.css separados).*
- **Instructor (Audio):** "Para este proyecto, usaremos Replit, otra herramienta online parecida a CodePen, pero que nos permite separar nuestros archivos como los profesionales. Tenemos un archivo index.html y otro llamado style.css. ¡Mira cómo todo el código que aprendimos encaja perfectamente aquí!"

**[Escena 3: Uniendo Piezas]**
- *(Visual: Se muestra rápidamente cómo se estructura un div, una imagen de perfil redonda y enlaces sociales).*
- **Instructor (Audio):** "Para tu proyecto final, crearás una tarjeta centrada usando nuestro truco margin: auto. Le pondrás tu nombre con un <h1>, una foto tuya o de tu avatar con la etiqueta <img>, una breve biografía en un párrafo <p> y, al final, una lista desordenada <ul> con enlaces <a> a tus redes o hobbies favoritos."

**[Escena 4: Revisión de Errores Comunes (Checklist)]**
- *(Visual: Un rayo rojo golpea la pantalla, revelando una lista de chequeo de errores comunes. El instructor tiene una lupa).*
- **Instructor (Audio):** "Antes de terminar, ¿qué pasa si algo no funciona? Revisa tres cosas: uno, ¿cerraste todas tus etiquetas HTML con la barra inclinada? Dos, ¿te olvidaste de poner los dos puntos : o el punto y coma ; en tu CSS? Y tres, revisa siempre que la ruta de tu imagen (src) esté bien escrita y tenga la palabra clave correcta. Si cumples con esta lista, tu página estará perfecta."

**[Escena 5: Cierre, Despedida y Próximos Pasos]**
- *(Visual: El sitio del proyecto final terminado y publicado con su URL. El instructor se despide con la mano).*
- **Instructor (Audio):** "Tu página está lista para publicarse al mundo. El desarrollo web es un camino de práctica constante, así que sigue experimentando colores, formas y etiquetas. Hay muchas más bibliotecas por descubrir. ¡Gracias por participar y mucho éxito en tus futuros proyectos, desarrollador!"

## 3. Código de Inicio (Starter Code)

*Plataforma: Replit (Plantilla)*

**HTML (index.html):**
`html
<html lang="es">
<head>
  <title>Mi Perfil Personal</title>
  <!-- Esto enlaza tu HTML con tu CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  
  <div class="tarjeta-perfil">
    <!-- Tu contenido va aquí: Imagen, nombre, bio, lista de enlaces -->
    
  </div>

</body>
</html>
`

**CSS (style.css):**
`css
body {
  font-family: "Arial", sans-serif;
  background-color: #fce4ec;
}

.tarjeta-perfil {
  background-color: white;
  width: 300px;
  /* ¡Usa el truco mágico para centrar! */
  
  /* Añade padding para dar espacio interior */
  
  /* Extra: vamos a darle bordes redondeados */
  border-radius: 15px;
}

/* Modifica el texto e imágenes como gustes */
`

## 4. Código Final (Solution)

**HTML (index.html):**
`html
<html lang="es">
<head>
  <title>Perfil de Estudiante</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  
  <div class="tarjeta-perfil">
    <img src="https://images.unsplash.com/photo-1544716186-0428e2c6cb51" alt="Avatar divertido">
    <h1>Ana Pérez</h1>
    <p>¡Hola! Me encanta el desarrollo web y los videojuegos de aventuras.</p>
    
    <h2>Mis Enlaces</h2>
    <ul>
      <li><a href="https://github.com">Mi GitHub</a></li>
      <li><a href="https://ejemplo.com">Mi Blog</a></li>
    </ul>
  </div>

</body>
</html>
`

**CSS (style.css):**
`css
body {
  font-family: "Arial", sans-serif;
  background-color: #fce4ec;
  /* Espacio extra arriba */
  padding-top: 40px;
}

.tarjeta-perfil {
  background-color: white;
  width: 300px;
  /* Truco para centrar */
  margin: auto;
  /* Espacio interior generoso */
  padding: 30px;
  border-radius: 15px;
  text-align: center; /* Centrar todo el texto */
}

/* Haciendo la imagen bonita y redonda */
img {
  width: 150px;
  border-radius: 50%;
}

/* Color para nuestros enlaces */
a {
  color: #c2185b;
}
`

## 5. Actividad Práctica

**Reto Final (15-20 minutos): ¡Construye tu Perfil!**
1. Abre tu plantilla en Replit y ve al archivo index.html.
2. Dentro de tu <div class="tarjeta-perfil">, construye todo lo que aprendimos: Pon una foto tuya (<img>), tu nombre (<h1>), un párrafo sobre ti (<p>) y un par de enlaces (<a>) en una lista.
3. Luego, ve a style.css y dale amor a tu tarjeta. Usa margin: auto; para centrarla en la pantalla.
4. Juega con los valores de ackground-color, añade padding: 20px; para que respire.
5. ¡Corre tu código, revisa si falló algo (recuerda los puntos y comas ;), y obsérvalo brillar! Tienes tu propia página web.
