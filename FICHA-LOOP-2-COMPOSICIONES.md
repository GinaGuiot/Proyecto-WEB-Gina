# Ficha de scroll 2 · Composiciones visuales

## Propósito
Reunir en una misma zona de scroll las tres lecturas visuales de CHROMA. Cada composición aparece en una ficha vertical con título y explicación.

## Composición 1 · Universo de artistas
Cada círculo representa un artista. El tamaño corresponde al tiempo de escucha y el color al género musical. Al pasar el cursor se muestran artista, género y minutos escuchados; en móvil, la información debe poder consultarse al tocar el círculo.

## Composición 2 · Anillos por año
Propuesta visual: un anillo concéntrico por año. Los puntos representan artistas; su tamaño indica las horas escuchadas y el color, el género. Permite comparar la actividad entre años.

**Estado:** la web contiene una versión exploratoria con datos de ejemplo para 2018–2026. Confirmar el periodo y las variables con la exportación real antes de aprobarla.

## Composición 3 · Ritmo semanal
Propuesta visual: una matriz que cruza los días de la semana con las horas del día. La intensidad puede representar minutos o reproducciones y el color puede distinguir géneros.

**Estado:** la web contiene una versión de muestra generada con valores ilustrativos. Solo se podrá validar si la exportación incluye marcas de fecha y hora suficientes.

## Comportamiento del scroll
- La primera vista presenta las tres composiciones juntas en una fila horizontal, también en móvil.
- Al avanzar por el scroll, cada composición se expande progresivamente a pantalla completa y se conecta con la siguiente.
- Cuando una composición está activa, las otras dos no quedan visibles detrás ni superpuestas.
- La barra superior permanece fija y conserva el logo pequeño.
- Las explicaciones se presentan como texto independiente del lienzo visual, sin encerrar la composición en un rectángulo.
- La transición respeta la preferencia del sistema por reducir el movimiento.

## Criterios de aceptación
- Se muestran tres composiciones distintas, primero juntas y luego una a una.
- Cada ficha explica qué variable representan las formas, tamaños y colores.
- Las propuestas 2 y 3 se identifican como provisionales hasta validarlas con los datos.
- La primera composición permite consultar artista, género y minutos.
- Los datos ficticios nunca se presentan como hallazgos de la escucha personal.
- El contenido se adapta a móvil y mantiene los textos legibles.
