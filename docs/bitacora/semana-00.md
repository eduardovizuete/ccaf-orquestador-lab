# Semana 0 — Habilitación (7-13 sept)

## Día 1 (lunes 7 sept)

### Hecho
- Notebook `Katas_CCAF_Colab.ipynb` subido a Colab y guardado como copia única en Drive.
- Setup global pasos 1-4 ejecutados sin errores.
- `workspace-demo/` verificado (auth, payments, tests, CLAUDE.md de ejemplo).

### Preguntas / aclaraciones
- Qué es Colab, celdas, entorno de ejecución (efímero — se pierde al desconectar).
- Qué es `katas._shared`: módulo común a las 30 katas. `bootstrap(budget_calls=N)` limita llamadas al modelo por kata. `logger` deja ver el comportamiento del agente paso a paso.

### Pendientes
- Pasos 5-6 del setup (API key) — bloqueados hasta Sesión 1.

---

## Día 2 (martes 8 sept)

### Hecho
- Repo `ccaf-orquestador-lab` creado con estructura de práctica (`src/`, `tests/`) + documentación (`docs/bitacora`, `docs/preguntas-guia`, `docs/entregables`, `docs/semaforo-task-statements.md`) + `CLAUDE.md` inicial.
- README de Módulo 1 (Accessing Claude with the API) leído: 9 lecciones, sin notebook propio, ejercicios se resuelven en la plataforma Claude Academy.
- Identificado el kata equivalente de refuerzo: `kata_001_agentic_loop`.

### Comandos ejecutados
- `git init`
- `git add .`
- `git commit -m "Setup inicial: estructura de práctica + documentación CCAF"`

### Preguntas / aclaraciones
- Diferencia clave del Módulo 1: el curso enseña *prefill del assistant* (` ```json ` + `stop_sequences`) para salidas estructuradas — sirve para el quiz de la plataforma, pero **no** es el método de las katas ni del examen. Las katas usan `tool_choice` forzado sobre JSON Schema (kata 005) porque valida y falla cerrado.

### Pendientes
- Completar las 9 lecciones del Módulo 1 en `academy.claude.com/courses/building-with-the-claude-api`.
- Opcional: `kata_001_agentic_loop` como refuerzo.

---

## Notas / dudas generales
-