# Criterios de desarrollo y toma de decisiones

## Objetivo
Establecer unas reglas comunes para implementar, revisar y mantener **Proyecto-WEB-Gina**. Aplicar estos criterios junto con los requisitos concretos que se vayan definiendo para cada funcionalidad.

## Orden de prioridad
Cuando haya decisiones que entren en conflicto, seguir este orden:
1. Instrucciones explícitas de la responsable del proyecto.
2. Requisitos y decisiones documentados del proyecto.
3. Funcionamiento correcto y seguridad.
4. Accesibilidad y facilidad de uso.
5. Mantenibilidad, claridad y rendimiento.
6. Preferencias estéticas o mejoras opcionales.

No sustituir un requisito explícito por una preferencia técnica propia. Si existe una contradicción, detener el cambio afectado y consultarla.

## Antes de modificar
- Leer `log.md`, `personalidad.md`, `criterio.md` y los documentos relevantes.
- Inspeccionar la estructura y el código existente antes de proponer una implementación.
- Identificar las dependencias, convenciones y patrones que ya utiliza el proyecto.
- Delimitar el alcance del cambio y evitar modificaciones no relacionadas.
- No asumir que una tecnología, framework o herramienta está instalada sin comprobarlo.

## Calidad del código
- Preferir soluciones simples, legibles y coherentes con la arquitectura existente.
- Reutilizar componentes y estilos cuando tenga sentido; evitar duplicaciones innecesarias.
- Usar nombres descriptivos y mantener una estructura consistente.
- Evitar dependencias nuevas si la funcionalidad puede resolverse razonablemente con lo que ya existe.
- No introducir código, configuraciones o archivos que no tengan una finalidad clara.
- Mantener separados, cuando corresponda, contenido, presentación y lógica.
- No incluir credenciales, contraseñas, claves privadas ni datos sensibles en el repositorio.

## Interfaz, accesibilidad y adaptación
- Diseñar para distintos tamaños de pantalla, empezando por una estructura adaptable.
- Usar HTML semántico y controles adecuados para cada interacción.
- Mantener contraste suficiente, foco visible, etiquetas comprensibles y navegación por teclado.
- Añadir textos alternativos útiles a las imágenes informativas.
- No depender únicamente del color para comunicar estados.
- Comprobar que los enlaces, botones, formularios y navegación tengan un comportamiento claro.

## Seguridad y datos
- Validar los datos recibidos y no confiar automáticamente en entradas del usuario.
- Evitar mostrar información privada o técnica innecesaria en la interfaz.
- No desactivar mecanismos de seguridad para resolver problemas de forma rápida.
- Tratar errores y datos externos de forma segura.

## Verificación
- Ejecutar las comprobaciones disponibles y adecuadas al cambio: pruebas, compilación, lint o revisión manual.
- Revisar los cambios para detectar errores, regresiones y modificaciones accidentales.
- No afirmar que algo está probado si no se ha ejecutado la comprobación correspondiente.
- Si no es posible verificar una parte, dejar constancia de la limitación.

## Git y documentación
- Realizar cambios pequeños y con mensajes de commit descriptivos.
- No sobrescribir el historial de `log.md`; añadir una entrada al final en cada sesión de trabajo.
- Registrar objetivos, archivos modificados, decisiones, verificaciones, incidencias y próximos pasos.
- No modificar `personalidad.md` ni `criterio.md` sin consultar previamente.
- No eliminar ni reemplazar contenido existente sin autorización o una necesidad justificada y explicada.

## Gestión de dudas y problemas
- Diferenciar hechos comprobados, hipótesis y propuestas.
- Si una decisión puede afectar al diseño, al alcance o a datos existentes, pedir confirmación antes de continuar.
- Si aparece un bloqueo, explicar qué se intentó, qué resultado se obtuvo y qué falta para resolverlo.
- Priorizar corregir la causa del problema frente a aplicar soluciones provisionales poco claras.

## Regla de cierre de sesión
Antes de terminar:
1. Resumir los cambios realizados.
2. Indicar las comprobaciones ejecutadas y sus resultados.
3. Anotar decisiones y asuntos pendientes en `log.md`.
4. Proponer el siguiente paso concreto, sin dar por terminado lo que no se haya verificado.
