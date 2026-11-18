# Desmontador de reels de referencia

## Objetivo

Descubrir decisiones narrativas, de ritmo y presentación que puedan inspirar contenido original. El desmontaje no consiste en copiar el guion ni en declarar que una característica causó la viralidad.

## Entrada

Una URL o archivo de video que el usuario eligió como referencia.

## Paso 0 — Determinar si es un outlier

Un número alto de vistas por sí solo no basta. Se compara el reel con el rendimiento habitual del mismo creador.

1. Recoge, cuando sea posible, plataforma, URL, autor, fecha de publicación, edad del video al medirlo, vistas, likes y comentarios.
2. Obtén entre 10 y 20 publicaciones recientes del mismo creador, preferentemente del mismo formato y plataforma.
3. Usa la **mediana** de vistas como referencia principal; anota también el rango y la media si ayudan a entender la distribución.
4. Compara piezas de antigüedad parecida. Si los videos tienen edades muy diferentes, marca la comparación como limitada.
5. Calcula: `ratio = vistas del reel / mediana de vistas de la muestra comparable`.
6. Interpreta el ratio como señal de selección, no como explicación causal. Un ratio alto permite priorizar el análisis; uno bajo no impide estudiar una técnica interesante.
7. Si no se consiguen datos suficientes, etiqueta el resultado como **outlier no verificable**. No inventes promedios ni ratios.

Como orientación de cribado, 3x puede tratarse como candidato destacado y 5x como candidato fuerte. Son umbrales operativos, no leyes universales. Añade siempre el tamaño de muestra y las limitaciones.

## Paso 1 — Acceso y descarga

- Intenta obtener el video en una calidad suficiente para analizarlo.
- Si falla por login, bloqueo, región o limitación técnica, informa el fallo.
- No describas escenas que no pudiste ver.
- Respeta los términos de la plataforma y los derechos del material. El uso de referencia no autoriza a republicar ni copiar la obra.

## Paso 2 — Transcripción

- Transcribe con marcas de tiempo cuando el audio esté disponible.
- Separa voz, diálogos, texto en pantalla y sonidos relevantes.
- Marca palabras dudosas como `[inaudible]` o `[posible: ...]`; no adivines.
- La transcripción sirve para analizar ritmo y recursos. La ficha debe priorizar beats y extractos breves necesarios para documentar, no convertirse en una copia reutilizable del guion completo.

## Paso 3 — Análisis visual y sonoro

1. Extrae fotogramas en intervalos razonables y en cada cambio importante. Un fotograma por segundo puede servir como punto de partida, pero no es obligatorio ni suficiente para todos los videos.
2. Identifica planos, acciones, texto, transiciones, movimiento y cambios de escena.
3. Anota únicamente lo que se observa. Distingue claramente cualquier interpretación.
4. Relaciona, en una línea temporal, imagen, voz, texto y sonido.
5. Si se usa una herramienta de visión, revisa manualmente las observaciones dudosas.

## Paso 4 — Ficha de desmontaje

Guarda `FICHA-<plataforma>-<autor>-<fecha>.md` con:

### A. Datos y comparabilidad
- URL, plataforma, autor, fecha de publicación y fecha de consulta.
- Vistas, likes, comentarios y antigüedad del reel al medirlo.
- Tamaño de la muestra del creador, mediana, ratio y limitaciones.
- Etiqueta: outlier fuerte, candidato, no outlier o no verificable.

### B. Contenido
- Tema y promesa central.
- Transcripción por beats con tiempos y extractos breves relevantes.
- Qué ocurre visualmente en cada beat.
- Texto en pantalla.
- Música, voz, efectos, silencios y cambios sonoros.

### C. Construcción narrativa
- Gancho verbal y visual.
- Pregunta o tensión que mantiene la atención.
- Contexto que entrega y cuándo lo entrega.
- Progresión de información o conflicto.
- Revelación, giro o recompensa, si existe.
- Forma de cerrar y CTA.

### D. Hipótesis de funcionamiento
Escribe de 1 a 3 hipótesis concretas. Cada una debe citar una observación y explicar qué efecto podría producir. No uses frases vacías como «está bien editado» o «engancha mucho».

Ejemplo de formulación: «La pieza muestra el resultado antes de explicar la causa; esto podría crear una pregunta concreta que el desarrollo promete resolver».

### E. Estructura abstraída
Describe el mecanismo sin tema ni frases originales: por ejemplo, «consecuencia desconcertante → contexto mínimo → tres indicios → explicación parcial → pregunta abierta».

### F. Límites
Anota qué puede depender del creador, la audiencia, el tema, la actualidad, la distribución o la calidad de producción. Señala qué no se puede concluir con un solo caso.

## Paso 5 — Extraer patrones

Propón patrones para `HOOKS.md`, `ESTRUCTURA.md`, `RETENCION.md`, `PLANOS.md` o `CTA.md`.

Cada patrón nuevo debe incluir:

- Código y nombre.
- Observación exacta que lo inspira.
- Mecanismo posible.
- Contexto donde podría funcionar.
- Contexto donde probablemente no convenga.
- Identificador de la ficha que lo respalda.
- Estado inicial **provisional**.

Si ya existe, añade la ficha como otro ejemplo, incluso cuando muestre una excepción. No eleves una regla a respaldada por un solo reel.

## Reglas de integridad

- Sin video o acceso suficiente, no se afirma que se desmontó visualmente.
- Sin transcripción verificable, no se inventan palabras exactas.
- Observación e interpretación deben aparecer separadas.
- Nunca se copia el guion del creador para publicar una versión equivalente.
- Una pieza muy vista no prueba por sí sola qué causó su rendimiento.
