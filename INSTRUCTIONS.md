# INSTRUCTIONS · CHROMA

## Identidad visual y estructura por scroll

QUIERO: Una web de CHROMA con una identidad visual reconocible, dos zonas de scroll y tres composiciones gráficas relacionadas con los datos de Spotify.

SERÁ BUENO SI:
- La tipografía de toda la web es Instrument Serif.
- El fondo es grafito, el texto legible y los acentos de color vivos y coherentes.
- El logo pequeño, formado solo por las seis barras de color, aparece arriba a la izquierda.
- El logo grande con las letras CHROMA aparece en la portada. Las letras están estáticas y las barras descansan sobre una línea base fija; solo cambia su altura desde arriba, con un movimiento sutil.
- La primera zona de scroll contiene el logo grande, una introducción breve y un botón «Empezar».
- «Empezar» desplaza a la segunda zona, donde las composiciones se presentan en fichas verticales con título y explicación.
- Las tres composiciones se entienden como partes de una misma experiencia, no como gráficos independientes.
- La web funciona con teclado y móvil. La información que aparece al pasar el cursor también se puede consultar tocando o enfocando el elemento.

NO SIRVE SI:
- Se mueven las letras o la base del logo durante la animación.
- El movimiento desplaza las barras completas en vez de alargar y acortar su parte superior.
- La página parece un dashboard genérico o utiliza los colores como adorno sin significado.

LO SABRÉ PORQUE: Al entrar se ve la identidad de CHROMA; al pulsar «Empezar» se llega a las visualizaciones y cada elemento tiene una función comprensible.

## 1. Universo de artistas — requisito confirmado

QUIERO: Una composición de círculos para explorar los artistas y los hábitos de escucha.

SERÁ BUENO SI:
- Cada círculo representa un artista de la exportación real de Spotify.
- El color identifica el género musical y el tamaño se calcula a partir de los minutos escuchados.
- Al pasar el cursor por cada círculo se muestran el nombre del artista, el género y los minutos de escucha.
- La misma información es accesible con foco de teclado y toque en pantallas táctiles.
- Los círculos se pueden explorar sin que las etiquetas o la acumulación hagan ilegible la composición.
- Los datos provisionales se identifican claramente como ejemplos.

NO SIRVE SI:
- Los artistas, géneros o minutos inventados se presentan como datos reales.
- El tamaño no corresponde al tiempo de escucha o el color no tiene una leyenda comprensible.

## 2. Anillos por año — propuesta pendiente de validación

La web muestra una propuesta de anillos concéntricos, uno por año; los puntos representan artistas, con tamaño por tiempo de escucha y color por género.

Antes de aprobarla:
- Confirmar que la exportación permite calcular el tiempo por artista y año.
- Confirmar el periodo temporal que muestran los anillos.
- Explicar visualmente el significado de los anillos y sus escalas.

## 3. Ritmo semanal — propuesta pendiente de validación

La web muestra una matriz de ejemplo que cruza los días de la semana con las horas del día. La intensidad puede representar minutos o reproducciones y el color puede distinguir géneros.

Antes de aprobarla:
- Confirmar que la exportación contiene fecha y hora de reproducción.
- Elegir una escala que no oculte los momentos con menos actividad.
- Asegurar que esta lectura temporal aporta información distinta al universo de artistas y a los anillos por año.

Las composiciones 2 y 3 son propuestas para valorar, no decisiones cerradas. Si los campos disponibles no permiten construirlas con rigor, presentar alternativas basadas en datos que sí existan.

## Datos y transparencia
- No inventar artistas, géneros, reproducciones, minutos ni patrones.
- No mostrar como hallazgos las hipótesis antes de comprobarlas con los datos.
- Mantener las etiquetas de «datos de ejemplo» mientras la web use contenido provisional.
- Definir la clasificación de géneros y su paleta después de revisar la exportación.

## Publicación
- Repositorio: https://github.com/GinaGuiot/Proyecto-WEB-Gina
- Web publicada: https://ginaguiot.github.io/Proyecto-WEB-Gina/
- El despliegue de GitHub Pages desde la rama main terminó correctamente el 24/11/2026.
