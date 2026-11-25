# CONTEXT · CHROMA
Última actualización: 25/11/2026

## La pregunta
¿Cómo pueden transformarse los hábitos de escucha musical de una persona en una identidad visual mediante el color, las formas y la visualización de datos?

## El proyecto
CHROMA convierte los datos personales de escucha de Spotify en una identidad visual. El color identifica géneros musicales y las formas representan artistas, tiempo y patrones de escucha.

## Los datos
- Fuente prevista: exportación personal de Spotify.
- Variables de interés: artista, género musical, fecha y hora de escucha y minutos escuchados, cuando estén disponibles.
- La web presenta el periodo 2018–2026; confirmar que la exportación real cubre ese intervalo.
- Las visualizaciones actuales usan datos ilustrativos. No presentarlos como resultados de la escucha personal.

## Identidad visual
- Tipografía: Instrument Serif.
- Fondo grafito, texto claro y acentos cromáticos naranja, amarillo lima, verde, azul, magenta y rojo.
- El logo pequeño, compuesto por las seis barras sin letras, permanece arriba a la izquierda en la cabecera fija.
- El logo grande CHROMA aparece en la portada. Las letras permanecen estáticas y alineadas sobre una base recta; solo cambia suavemente la altura de las barras desde su parte superior.

## Estructura de la experiencia
La web tiene dos loops de scroll:

1. **Portada y presentación:** logo grande, introducción general de CHROMA y botón «Ver mi universo musical». El texto de bienvenida introduce el proyecto sin describir una visualización concreta.
2. **Composiciones:** primero se ven las tres propuestas juntas en una fila horizontal. Con el scroll, cada una se despliega progresivamente a pantalla completa y conecta con la siguiente. La composición activa se muestra sola; las otras no quedan visibles detrás. La barra superior conserva el logo pequeño durante el recorrido.

La página respeta la preferencia del sistema por reducir el movimiento y se adapta a pantallas pequeñas.

## Composiciones
### 1. Universo de artistas
Cada círculo representa un artista. El tamaño depende de los minutos de escucha y el color representa el género musical. Al pasar el cursor por un círculo se muestran artista, género y minutos; en dispositivos táctiles se puede consultar tocándolo.

### 2. Anillos por año — propuesta provisional
Anillos concéntricos para explorar cambios en las escuchas a lo largo del tiempo. La versión actual es exploratoria y emplea datos de ejemplo. Confirmar periodo, variables y escala con la exportación antes de tratarla como definitiva.

### 3. Ritmo semanal — propuesta provisional
Matriz que cruza días de la semana y horas del día. La versión actual emplea valores ilustrativos. Solo se podrá validar si la exportación incluye marcas de fecha y hora suficientes.

Las propuestas 2 y 3 siguen pendientes de validación. La paleta de géneros también debe confirmarse con los datos reales.

## Decisiones
- El proyecto se llama CHROMA.
- Spotify es la fuente de datos prevista.
- El recorrido tiene dos loops: portada y composiciones.
- La web contiene tres composiciones gráficas; primero aparecen juntas en horizontal y después se exploran una a una con scroll.
- Instrument Serif y las dos versiones del logo forman parte de la identidad visual.

## Web y repositorio
- Web publicada: https://ginaguiot.github.io/Proyecto-WEB-Gina/
- Repositorio: https://github.com/GinaGuiot/Proyecto-WEB-Gina
- La web se publica con GitHub Pages desde la rama main.

## Estado y próximos pasos
- Portada, navegación por scroll y tres visualizaciones exploratorias publicadas.
- Los nombres, géneros, minutos y patrones siguen siendo ejemplos hasta integrar y validar la exportación real.
- Confirmar el periodo y los campos de la exportación de Spotify.
- Validar las propuestas 2 y 3, y definir la paleta de géneros a partir de los datos disponibles.
