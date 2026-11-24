# CONTEXT · CHROMA
Última actualización: 24/11/2026

## La pregunta
¿Cómo pueden transformarse los hábitos de escucha musical de una persona en una identidad visual mediante el color, las formas y la visualización de datos?

## El proyecto
CHROMA convierte los datos personales de escucha de Spotify en una identidad visual. El color identifica géneros musicales y las formas representan artistas, tiempo y patrones de escucha.

## Los datos
- Fuente principal: exportación personal de Spotify.
- Variables de interés: artista, género musical, fecha y hora de escucha, y minutos escuchados cuando estén disponibles.
- El periodo 2018–2026 aparece en la web publicada; hay que confirmarlo con la exportación real.
- No inventar artistas, géneros, minutos, recuentos ni tendencias. Las visualizaciones actuales usan datos ilustrativos y los señalan como ejemplos.

## Identidad visual y web
- Tipografía: Instrument Serif.
- Fondo grafito, texto claro y acentos cromáticos vivos. El logo usa barras naranja, amarillo lima, verde, azul, magenta y rojo.
- Hay dos versiones del logo: el símbolo pequeño de barras sin letras va arriba a la izquierda; el logo principal CHROMA, con letras, aparece grande en la portada.
- En el logo grande, las letras permanecen quietas y alineadas en una base recta. Solo se alargan y acortan ligeramente las barras por su parte superior; la base no se mueve.
- El recorrido tiene dos zonas de scroll: una portada de bienvenida y una zona de visualizaciones.
- La portada presenta el logo grande, una breve introducción y el botón «Empezar», que lleva a las composiciones.
- La zona de visualizaciones contiene tres composiciones en fichas verticales, cada una con título y explicación.

## Composiciones
### 1. Universo de artistas — implementada
Cada círculo representa un artista. El color representa su género musical y el tamaño depende del tiempo de escucha. Al pasar el cursor por un círculo se muestran el nombre del artista, el género y los minutos escuchados. En móvil, la información debe poder consultarse al tocar el círculo.

### 2. Anillos por año — propuesta visual implementada con datos de ejemplo
Una composición de anillos concéntricos, uno por año. Los puntos representan artistas; su tamaño indica el tiempo de escucha y el color, el género. Permite observar cómo cambia la escucha entre años. Confirmar el periodo y los campos con la exportación real antes de considerarla definitiva.

### 3. Ritmo semanal — propuesta visual implementada con datos de ejemplo
Una matriz de días de la semana y horas del día. La intensidad representa minutos o reproducciones y el color distingue categorías musicales. Aporta una lectura del momento en que se escucha música. Solo se podrá convertir en composición final si la exportación incluye marcas de fecha y hora suficientes.

Las composiciones 2 y 3 siguen siendo propuestas conceptuales pendientes de validación con datos reales y confirmación de la responsable. La paleta de géneros también queda pendiente de definir a partir de los datos.

## Referentes y criterio
Interesan la visualización de datos con personalidad, el arte generativo y una identidad cromática comprensible. Se descartan los dashboards estadísticos convencionales y el uso de color o forma como decoración sin relación con los datos.

## Decisiones
- El proyecto se llama CHROMA.
- Spotify es la fuente principal de datos.
- El género se relaciona con el color y el tiempo de escucha puede determinar el tamaño de cada círculo.
- La web reúne tres composiciones distintas y coherentes.
- Instrument Serif y las dos versiones del logo quedan como decisiones de identidad visual.

## Hipótesis (sin comprobar)
- Los hábitos musicales pueden representarse mediante una identidad cromática propia.
- La relación entre artistas y géneros puede revelar agrupaciones o patrones.
- Las composiciones pueden ofrecer distintas lecturas de una misma escucha.

## Web y repositorio
- Repositorio: https://github.com/GinaGuiot/Proyecto-WEB-Gina
- Web publicada: https://ginaguiot.github.io/Proyecto-WEB-Gina/
- GitHub Actions completó correctamente la compilación y el despliegue de la web el 24/11/2026.
- La URL corresponde a la versión de CHROMA publicada desde index.html en main.

## Estado y próximos pasos
- Publicadas la portada con botón «Empezar» y las tres fichas de composición.
- Las cifras, artistas, géneros y patrones siguen siendo ejemplos; no representan todavía una exportación real.
- Confirmar periodo y campos de la exportación de Spotify.
- Validar las propuestas 2 y 3 y definir la paleta de géneros con datos reales.
- Sustituir los datos de muestra cuando esté disponible la exportación.
