# Lección 6: Tipografía y estilo

## Video de la Clase
*Enlace al video de YouTube:* [Añadir enlace aquí]

## Entorno de Práctica
*Empieza a programar de inmediato (¡Sin instalar nada!):*
- **[Abrir Replit - Tipografia y estilo](https://codepen.io/pen)**
- **[Abrir JDoodle - Tipografia y estilo](https://codepen.io/pen)**

## Transcripción / Notas de la Clase

¡Hola de nuevo, creadores! Imagina que lees una solicitud formal escrita con letras de cómic; nadie te tomaría en serio. La letra, o "tipografía", comunica emociones. Hoy le pondremos personalidad a nuestra página cambiando sus fuentes, tamaños y alineaciones.

**Cambiando la Fuente (`font-family`)**
Para cambiar el tipo de letra en CSS, usamos la propiedad `font-family`. Veamos cómo cambia nuestro texto principal si le damos un estilo limpio y sin adornos conocido como *sans-serif*, por ejemplo, 'Arial' o 'Helvetica'. Escribiremos: `font-family: Arial, sans-serif;`.

Cuando estructuramos esta propiedad, es importante entender cómo funcionan sus componentes:
- **Fuentes de respaldo:** Al escribir `font-family: Verdana, sans-serif;`, estamos dando una primera opción y una opción de respaldo. Le decimos al navegador: "usa Verdana si está disponible; si no, usa cualquier fuente genérica sin adornos (`sans-serif`)". Esto garantiza que la página se siga viendo bien aunque no todos los dispositivos tengan las mismas fuentes instaladas.
- **Diferencia entre Serif y Sans-serif:** Las fuentes *serif* tienen pequeños detalles o remates en las puntas de las letras. Las fuentes *sans-serif* no tienen esos remates y suelen verse más limpias en pantallas. Para empezar, las fuentes sans-serif como Arial, Verdana o Helvetica son una excelente elección porque se leen fácilmente.



> **¿Fuentes externas?:** Si quieres fuentes más increíbles, existe una biblioteca enorme y gratuita llamada Google Fonts. Si encuentras una fuente genial, como 'Roboto' o 'Pacifico', puedes importarla a tu proyecto. Para mantenerlo simple en esta clase, usaremos fuentes que ya vienen en todos los navegadores, pero ten en mente que internet está lleno de opciones.

**Tamaños y Jerarquía Visual (`font-size`)**
Un requisito para un buen diseño es guiar los ojos del visitante. A esto le decimos **jerarquía visual**: lo más importante debe ser lo más grande. 

Vamos a usar la propiedad `font-size` para darle a nuestro título `h1` un tamaño de `40px` (píxeles), y a nuestro párrafo un tamaño base de `18px`, logrando que la lectura sea mucho más cómoda y equilibrada.

**Alineando el Texto (`text-align`)**
Para rematar nuestra lección, a veces queremos que los títulos estén centrados. Con tan solo agregar `text-align: center;` en la regla de nuestro `h1`, el título se posicionará automáticamente en medio de la pantalla.

Ten en cuenta la siguiente buena práctica de lectura al alinear:
- Centrar un título puede hacerlo más llamativo y estético.
- Evita centrar textos largos o párrafos completos, ya que leer muchas líneas centradas puede cansar la vista del usuario. Es mejor dejar los párrafos largos alineados a la izquierda.

**Error Común de Escritura**
En CSS, muchas propiedades compuestas usan guiones obligatorios. Por ejemplo, se escribe `font-family` (no `font family`) y `font-size` (no `font size`). Si olvidas el guion y dejas un espacio, el navegador simplemente ignorará la instrucción. Cuando algo no cambie en tu pantalla, revisa primero el nombre exacto de la propiedad.

Hoy aprendiste que el texto también se diseña: la fuente define la personalidad, el tamaño construye la jerarquía y la alineación guía la atención. En la siguiente lección veremos espacios, bordes y cajas para ordenar la estructura visual.


## Código de Inicio

*Plataforma: CodePen*

**HTML:**
```html
<html lang="es">
  <body>
    <h1>Bienvenido a mi mundo</h1>
    <p>Este es mi primer diseño con jerarquía visual y tipografías geniales.</p>
  </body>
</html>
```

**CSS:**
```css
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
```

## Código Final

**HTML:**
```html
<html lang="es">
  <body>
    <h1>Bienvenido a mi mundo</h1>
    <p>Este es mi primer diseño con jerarquía visual y tipografías geniales.</p>
  </body>
</html>
```

**CSS:**
```css
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
```

## Actividad Práctica

**Reto (4 minutos): ¡Haz que se lea bien!**
1. En CSS, dentro de tu regla ody, agrega la propiedad ont-family y asígnale el valor Verdana, sans-serif;. Observa cómo cambian las letras al instante.
2. Ve a la regla de tu h1. Aumenta su tamaño dándole a la propiedad ont-size un valor de 40px;.
3. Haz que tu título sea el centro de atención añadiéndole 	ext-align: center;.
4. Finalmente, haz que el párrafo <p> se lea grande y claro. Ponle un ont-size de 18px; o 20px;.

## Referencias y Bibliografía

- **MDN Web Docs:** [Fundamental text and font styling / Estilo de texto básico](https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Fundamentals)
- **W3C HTML & CSS:** [Text Styling / Estilizando Texto en CSS](https://www.w3.org/Style/Examples/007/text.en.html)