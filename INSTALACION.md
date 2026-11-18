# Instalación — Máquina de Guiones v2.3 para Claude Code

## Qué corrige esta versión

La definición anterior estaba guardada como `guiones/skill.md`. Claude Code espera las Skills de proyecto en:

`.claude/skills/<nombre>/SKILL.md`

Esta versión ya utiliza la ruta y el nombre exactos:

`.claude/skills/guiones/SKILL.md`

Los documentos de metodología están dentro de la carpeta `references/` junto a `SKILL.md`.

## Cómo instalar

1. Descarga y descomprime este ZIP en la raíz del repositorio donde trabajas con Claude Code.
2. Conserva la carpeta oculta `.claude` (no la renombres ni la muevas).
3. Verifica que exista `.claude/skills/guiones/SKILL.md`.
4. Abre una sesión de Claude Code desde esa raíz. Si ya había una sesión abierta, inicia una sesión nueva para que vuelva a descubrir las Skills del proyecto.
5. Escribe `/guiones` y selecciónala si aparece en el selector.

## Cómo usarla

- `/guiones` — inicializa la máquina y muestra las operaciones disponibles. No genera un guion porque todavía no se ha indicado un tema.
- `/guiones CREAR GUION: [tema]` — inicia la máquina y ejecuta la creación del guion para ese tema.
- `/guiones DESCUBRIR IDEAS: [nicho]` — propone y prioriza ideas.
- `/guiones INVESTIGAR TEMA: [tema]` — investiga el tema antes de diseñar la narrativa.

También puedes invocarla sola y después elegir una operación en el mismo hilo.

## Comprobación

Después de instalar, confirma que Claude Code identifica `guiones` como Skill del proyecto. Si no aparece:

- comprueba que abriste Claude Code desde la raíz correcta del repositorio;
- revisa que la ruta y mayúsculas sean exactamente `.claude/skills/guiones/SKILL.md`;
- inicia una sesión nueva.

No es necesario instalar un plugin de organización para una Skill local del proyecto.
