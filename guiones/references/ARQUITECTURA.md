# Arquitectura de la máquina de guiones

**Versión:** 2.1  
**Objetivo inicial:** guiones originales para videos cortos de redes sociales, empezando por Facebook Reels.

## 1. Principio de diseño

La máquina tiene un motor narrativo independiente de las plataformas y adaptadores que ajustan la presentación a cada red. Un tercer componente aprende de las publicaciones reales.

No es una plantilla que rellena espacios ni una fábrica de frases virales. Es un sistema de decisiones editoriales: entiende el tema, busca qué vale la pena contar, diseña una experiencia narrativa y comprueba si el resultado cumple su promesa.

## 2. Tres capas

### Capa A — Motor de inteligencia narrativa

Responsabilidades:
- Entender el tema, el nicho, el público y el objetivo.
- Detectar si existe una historia o idea con suficiente valor.
- Investigar y separar hechos, testimonios, versiones, hipótesis y ficción.
- Encontrar ángulos originales y elegir uno con argumentos.
- Diseñar la progresión narrativa y escribir una locución natural.
- Revisar claridad, ritmo, veracidad, originalidad y recompensa para el espectador.

Esta capa no presupone una duración, una estructura ni un gancho universal.

### Capa B — Adaptador de plataforma

Responsabilidades:
- Aplicar las características y restricciones relevantes de la plataforma elegida.
- Ajustar la entrega: duración objetivo, orientación, legibilidad, ritmo, texto de apoyo, caption y CTA.
- Revisar las reglas actuales de recomendación, originalidad y publicación cuando el dato dependa de la plataforma.

La plataforma modifica la presentación y ciertos criterios de entrega; no debe deformar los hechos ni sustituir una buena historia por trucos algorítmicos.

### Capa C — Sistema de aprendizaje

Responsabilidades:
- Registrar el guion realmente publicado y las decisiones utilizadas.
- Registrar las métricas disponibles con fecha y antigüedad equivalente.
- Comparar cada publicación con la línea base del mismo canal y formatos razonablemente comparables.
- Formular hipótesis, buscar contraejemplos y proponer pruebas.
- Actualizar las bibliotecas sin elevar coincidencias aisladas a reglas.

## 3. Flujo operativo

### Fase 0 — Identificar la tarea

Reconocer si el usuario pide:
- Explorar un nicho o encontrar ideas.
- Evaluar una idea concreta.
- Investigar un tema.
- Crear un guion desde cero.
- Desmontar un Reel de referencia.
- Adaptar un guion existente a otra plataforma.
- Analizar resultados y aprender de una publicación.

No ejecutar etapas que no correspondan. Por ejemplo, una solicitud de ideas no necesita producir automáticamente un guion completo.

### Fase 1 — Comprender el encargo

Construir el brief con los datos disponibles. Identificar audiencia, necesidad/interés, promesa, objetivo, plataforma, duración solicitada, tono y límites. Preguntar solo por una información que cambie materialmente la decisión; en los demás casos, proponer supuestos explícitos.

### Fase 2 — Evaluar el potencial de la idea

Determinar:
- Qué tiene de interesante o útil.
- Qué pregunta, tensión, contraste o transformación puede sostenerla.
- Qué valor concreto recibe el espectador.
- Qué la diferencia de una explicación genérica.
- Si hay suficiente información o material visual para desarrollarla.

La máquina puede recomendar descartar, acotar o reformular una idea. No debe inflarla artificialmente.

### Fase 3 — Investigar, cuando corresponda

Seguir `INVESTIGACION.md`. No toda pieza requiere investigación factual: una historia ficticia, una opinión o una pieza creativa debe identificarse como tal y no simular verificación.

### Fase 4 — Diseñar la historia

Producir una ficha narrativa con:
- Idea central.
- Audiencia y motivo por el que podría importarle.
- Ángulo elegido y alternativas descartadas.
- Pregunta o tensión principal.
- Promesa y recompensa final.
- Estructura propuesta y función de cada beat.
- Límites de lo que puede afirmarse.

### Fase 5 — Diseñar y elegir el gancho

Generar varias alternativas realmente distintas. Evaluarlas por claridad, especificidad, interés, credibilidad y capacidad de entrega. Seleccionar una y explicar sus riesgos. No usar la puntuación como predicción de viralidad.

### Fase 6 — Escribir el guion

Seguir `GUION.md`. Escribir primero para el oído: el texto debe sonar natural en voz alta, no parecer un artículo comprimido. Las indicaciones visuales acompañan la intención narrativa y no reemplazan la locución.

### Fase 7 — Aplicar el adaptador de plataforma

Para Facebook Reels, seguir `FACEBOOK_REELS.md`. Aplicar solo los ajustes que aporten. Si un ajuste compromete la claridad, originalidad o veracidad, descartarlo.

### Fase 8 — Control de calidad

Seguir `EVALUACION.md`. Si falla una condición esencial de veracidad, promesa, comprensión u originalidad, corregir antes de entregar. Si solo hay una preferencia estética discutible, puede mostrarse como opción.

### Fase 9 — Entregar y aprender

Entregar el guion con su ficha de producción editorial. Después de la publicación, registrar los datos en `REGISTRO.md`. El resultado de una sola pieza es una observación, no una conclusión universal.

## 4. Formas de salida

### Salida breve — Idea
- Idea o tema.
- Audiencia probable.
- Ángulo propuesto.
- Por qué puede interesar.
- Riesgos o límites.

### Salida de desarrollo — Diseño narrativo
- Brief.
- Investigación resumida, si aplica.
- Ángulo elegido y alternativas.
- Promesa y estructura.
- Ganchos propuestos.

### Salida completa — Guion listo para producción
- Ficha del Reel.
- Gancho elegido y alternativas.
- Narración exacta por beats.
- Tiempo estimado por beat.
- Función narrativa de cada beat.
- Idea visual de apoyo y texto en pantalla cuando aporte.
- CTA opcional.
- Fuentes y advertencias de verificación.
- Decisiones editoriales y aspectos que convendría probar.

## 5. Reglas de decisión

1. La veracidad tiene prioridad sobre el impacto.
2. La promesa tiene que ser específica y cumplible.
3. La audiencia importa más que una tendencia genérica.
4. Cada beat debe aportar comprensión, tensión, emoción, contexto o recompensa.
5. Una técnica es una herramienta, no una obligación.
6. Una referencia sirve para estudiar mecanismos; no para copiar frases, secuencias distintivas ni la obra.
7. Las métricas describen resultados; por sí solas no explican causas.
8. El sistema debe poder decir «esta idea no da para un buen Reel».

## 6. Relación con la producción audiovisual

La máquina entrega el guion y un plan visual legible para el equipo o sistema de producción. No renderiza ni genera por sí misma el video, la voz, la música o los efectos. Las indicaciones visuales deben poder adaptarse a una producción original basada en recursos procedurales y código, cuando ese sea el flujo elegido.
