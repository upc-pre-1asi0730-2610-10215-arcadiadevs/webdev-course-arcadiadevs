# Lección 6: Tipografía y estilo

## 1. Estructura de Carpetas

Sugerimos organizar esta lección en el repositorio de la siguiente manera:

```text
/starter-files/lesson-06        # Archivo base listo para escribir el código en vivo
├── index.html
└── styles.css
/completed-examples/lesson-06   # El código final con las reglas CSS aplicadas correctamente
├── index.html
└── styles.css
```

## 2. Guion de Video
> **El poder de las letras**
> ¡Hola de nuevo! Imagina que lees una solicitud formal escrita con letras de cómic; nadie te tomaría en serio. La letra, o 'tipografía', comunica emociones. Hoy le pondremos personalidad a nuestra página cambiando sus fuentes y tamaños.
>
> **Cambiando la Fuente (font-family)**
> Para cambiar el tipo de letra, usamos la propiedad ont-family. Veamos cómo cambia nuestro texto principal si le damos un estilo limpio y sin adornos conocido como *sans-serif*, por ejemplo, 'Arial' o 'Helvetica'. Escribiremos: ont-family: Arial, sans-serif;.
>
> **Explicación de fuentes de respaldo**
> Cuando escribimos `font-family: Verdana, sans-serif;`, estamos dando una primera opción y una opción de respaldo. Le decimos al navegador: usa Verdana si está disponible; si no, usa cualquier fuente sin adornos, es decir, una `sans-serif`. Esto ayuda a que la página se siga viendo bien aunque no todos los dispositivos tengan exactamente las mismas fuentes.
>
> **Serif y sans-serif explicado simple**
> Las fuentes serif tienen pequeños detalles o remates en las puntas de las letras. Las fuentes sans-serif no tienen esos remates y suelen verse más limpias en pantalla. Para principiantes, las fuentes sans-serif como Arial, Verdana o Helvetica son una buena elección porque se leen fácilmente.
> 
> **Traer fuentes de internet (Google Fonts en CodePen)**
> ¿Quieres fuentes más increíbles? Hay una biblioteca enorme y gratuita llamada Google Fonts. Si encuentras una fuente genial, como 'Roboto' o 'Pacifico', puedes importarla a tu proyecto. Para mantenerlo simple, usaremos fuentes que ya vienen en todos los navegadores, pero ten en mente que internet está lleno de opciones de fuentes para obtener e instalar.
>
> **Tamaños y Jerarquía visual**
> Un requisito para un buen diseño es guiar los ojos del visitante. A esto le decimos *jerarquía visual*. Lo más importante debe ser lo más grande. Vamos a usar la propiedad font-size para darle a nuestro título h1 un tamaño de 40px (píxeles), y a nuestro párrafo un tamaño base de 18px, para que se lea fácil.
>
> **Alineando Sentimientos (text-align)**
> Para rematar nuestra lección, a veces queremos que los títulos estén centrados. Con tan solo agregar text-align: center; en la regla de nuestro h1, observa cómo el título se posiciona en medio de la pantalla.
>
> **Alineación y lectura**
> Centrar un título puede hacerlo más llamativo. Pero no siempre conviene centrar textos largos, porque leer muchas líneas centradas puede cansar. En este ejercicio centramoss el título para practicar `text-align`, pero cuando tengas párrafos largos, prueba dejarlos alineados a la izquierda para que sean más cómodos.
>
> **Pausa práctica guiada**
> Ahora es tu turno! Cambia el tamaño del párrafo. Prueba `18px`, luego `20px` y después `24px`. Pregúntate: ¿cuál se lee mejor?, ¿cuál se ve exagerado?, ¿cuál queda equilibrado con el título? No hay una única respuesta perfecta, pero sí hay decisiones más cómodas para el usuario.
>
> **Error común de escritura en propiedades**
> En CSS, muchas propiedades usan guiones. Por ejemplo, se escribe `font-family`, no `font family`; y se escribe `font-size`, no `font size`. Si una propiedad está mal escrita, el navegador simplemente la ignora. Por eso, cuando algo no cambie, revisa primero el nombre exacto de la propiedad.
>
> **Cierre ampliado**
> Hoy aprendiste que el texto también se diseña. La fuente define personalidad, el tamaño ayuda a leer y la alineación guía la atención. En la siguiente lección veremos espacios, bordes y cajas para que la página tenga una estructura visual más ordenada.
>