Commits
-1. He añadido el index. La estructura básica la he hecho presionanso "!" y tabulador. También he dejado lo que había añadido previamente en la clase como la ruta al css, los links e imágenes.

-2. He añadido las carpetas images y css, y un archivo .css dentro que me pone la página amarilla.

-3. Creo el readme desde github en otra rama (no se como ha pasado).
-4. Junto las ramas (lo ha hecho GitHub).

-5. Estructuro el readme.

-6. No se añade la carpeta hasta que meto algo dentro, ahora si creo la de images con una foto de Josema Gimenez.

-7. Hago cambios en el readme.

-8. He creado la carpeta de paginas y las paginas, sin contenido.

-9. Añado la página de la asignatura.

-10. Añado contenido básico y estructura a la página de fundamentos y unas pequeñas indicaciones de estilo para hacer el css luego (como comentarios). Como la alineacion de los titulos.

-11. Añado el fii.css (El estilo para la página de la asignatura), para su realización le he puesto "h1" y al tabular me lo ha rellenado como yo quería, con la alineación centrada, luego fijandome en ese he puesto el resto (h2 y p), y el de body lo he copiado del que ya tenia (estilo.css, el del index). Luego lo he añadido a la página con el comando que tenía en el index.

-12. He metido la descripción de la asignatura como parrafos.
    fii.css: Aquí he usado chatGPT para ver como poner margen en el texto, me ha dicho que ponga con 70ch que son 70 caracteres y lo he aumentado a 120. También que use la etiqueta "div" con una clase que he llamado contenido y me ha explicado como hacerla, usando un punto antes en el css ( .contenido )

-13. Añado estilo a la lista con la ayuda de Chaty para aumentar el espacio entre los elementos de la lista. También le he metido interlineado 1.3 porque 1.5 me parecía excesivo

-14. Termino de meter la info de la asignatura
-15. Añado cosas al readme.

-16. Añado los enlaces a las páginas en la principal con una barra negra arriba (barra de navegación entre páginas), en el DDD más detallado en la parte de estilo.css (DDD estilo.css -2-)

-17. Añado el icono de la página y los enlaces en la parte inferior de la página index para poder ir más rápido. (DDD más detallado) (DDD index.css -3-)

-18. Me he dado cuenta de que la clase contenido es general, ya que es el estilo que quiero, asi que la añado también al estilo.css y al grado.css. (grado.css -1-).
También he añadido la información del grado, (Detallado en el DDD, grado.html)
Aunque aún falta información.
También en este mismo commit añado la barra de navegación entre páginas en la página grado.
-19. Me faltaban los dos puntos / en las rutas de los enlaces a las páginas en  la de grado.html, lo que hacía que no funcionara, lo he arreglado.
-20. Commit inutil

-21. Añado info al DDD fii.css
-22. Añado la tabla de las asignaturas (Más detallado en DDD grado.html -5-)
Le añado estilo a esa tabla (Más detallado en DDD grado.css)
-23. Arreglo la numeración de los commits en el README.
-24. He metido los enlaces abajo y la barra de navegación entre páginas de arriba en la página de fii.
-25. He añadido el icono a las páginas fii y topic (como se repite para el resto ya no lo pondré detallado, esta en el apartado de index del DDD, así como en el apartado de topic.html -2- y fii.html -6-).
-26. Creo la estructura de la página contact.html
-27. Creo la estructura de la página about.html


---DDD---

--index.html y estilo.css--

2- Para añadir el desplegable y la barra de selección de página arriba he usado como referencia este video: https://www.youtube.com/watch?v=9nFQN1bt7kA
con un poco de ayuda de ChatGPT para que quede como quería. Lo he hecho con dos listas. Así lo he alineado arriba con fondo negro, he quitado que parezca un hipervinculo, y le he añadido hovers para que salga amarillo al pasar por encima y en el caso del grado un desplegable. Todo creando una clase llamada menu como aparece en el video.
3- He añadido enlaces al final de la página para mejorar la comunicación entre páginas, y he añadido una linea de copyright porque porque no. También he cogido una línea de código de otra web que ya hice en segundo de la ESO para añadir el icono a la página, la linea es: <link rel="shortcut icon" href="icon.ico>


--Fii.html y fii.css--

-Fii.html
(Todo el contenido sacado de la guía docente)
1- Añado contenido básico y estructura a la página de fundamentos y unas pequeñas indicaciones de estilo para hacer el css luego (como comentarios). Como la alineacion de los titulos.
2- Añado el fii.css (El estilo para la página de la asignatura), para su realización le he puesto "h1" y al tabular me lo ha rellenado como yo quería, con la alineación centrada, luego fijandome en ese he puesto el resto (h2 y p), y el de body lo he copiado del que ya tenia (estilo.css, el del index). Luego lo he añadido a la página con el comando que tenía en el index.
3- He metido la descripción de la asignatura como parrafos.
4- He terminado de meter la información, con distintos encabezados, poniendo cosas en negrita.
5- Copio la barra de navegación de la página de grado.html que es la misma.
y los enlaces de la parte inferior.
6- Le añado el icono a la página con la linea <link rel="shortcut icon" href="../icon.ico>


-fii.css: 
1- Aquí he usado chatGPT para ver como poner margen en el texto, me ha dicho que ponga con 70ch que son 70 caracteres y lo he aumentado a 120. También que use la etiqueta "div" con una clase que he llamado contenido y me ha explicado como hacerla, usando un punto antes en el css ( .contenido ). Las clases lo que hacen es aplicar un estilo unicamente a lo que esté marcado con esta clase.
Le he dicho a la IA que lo de poner margen en funcion de pixeles no era bueno y me ha explicado una forma de hacerlo en función de porcentajes de la ventana las unidades que usa para los márgenes son 5vh que es para que tenga un margen superior e inferior y significa 5% de la altura de la ventana, el auto hace que la horizontal se centre automáticamente. El 1 rem es para añadir espacio entre elementos de la lista y el 3vw del padding es el 3% del ancho de la página pero aún no entiendo del todo que es el padding, pero queda bien.
2- Añado estilo a la lista con la ayuda de Chaty para aumentar el espacio entre los elementos de la lista. También le he metido interlineado 1.3 porque 1.5 me parecía excesivo (line-height).
3- Copio el estilo (.menu) de la barra de navegación y el estilo (.pie) de los enlaces de la parte inferior.


--grado.html y grado.css--

-grado.html-
1- Añado la estructura básica
2- Copio la barra de navegación de páginas del index.html (añado ../ antes de cada ruta.)
3- Copio el copyright y enlaces del index para facilitar navegación pero el "align center" no funcionaba y he tenido que incluirlo en el css (grado.css -3-)
4- He sacado la información de los objetivos de https://notas.ufv.es/documentos/objetivos_formativos_informatica.pdf y el plan de estudios de la web de la UFV.
El resto de la información a cerca del grado de los apuntes de la asignatura.
5- He buscado en google como hacer una tabla y la versión integrada de gemini en el navegador me ha respondido explicandome las etiquetas, luego he puesto "table" en la página y visual studio ha rellenado la estructura solo.
He insertado la info y el enlace de la página dedicada a FII (info sacada de las guías docentes). Luego le he metido un borde a la tabla de 1 para que se vea como una tabla y no como un texto raro.


-grado.css-
1- He copiado el fii.css
2- Copio el estilo de la barra de navegación de páginas de estilo.css (.menu)
3- Creo la Clase "Pie" para el pie de página ya que poner que se alinee al centro no funcionaba porque priorizaba el css del parrafo a lo que pusiera en el html
4- He creado las clases negrita (pone el texto en negrita y lo centra), enlace_bonito (pone el enlace negro) con un hover para que al pasar por encima se ponga rojo, y la clase color para poner el texto en azul.
5- He metido un padding a los elementos de la tabla de 1% de la anchura y altura de la ventana para que no quedara pegado a los bordes de la tabla (creo que ya entiendo que es el padding aunque he tenido que buscar otra vez como se hacía en chatGPT para entenderlo del todo.)


--topic.html y topic.css

-topic.html-
1- Añado la estructura básica de la misma forma que lo hice con las otras.
2- Añado el icono igual que con las otras con la linea <link rel="shortcut icon" href="../icon.ico>


-topic.css-


--contact.html y contact.css--

-contact.html-
1- Creo la estructura básica con el !


-contact.css


--about.html y about.css--

-about.html-
1- Creo la estructura básica con el !

-about.css-


--net.html y net.css--

-net.html-


-net.css-
