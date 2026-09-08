# CLAUDE.md

Este repositorio combina dos propósitos: código de práctica y documentación del
Programa Orquestador CCAF. Tenlo en cuenta al sugerir cambios o generar contenido.

## Convenciones de código (src/, tests/)

- Python 3.11+, tipado con type hints donde aporte claridad.
- Cada módulo bajo `src/` es independiente — no asumas dependencias cruzadas salvo
  que estén explícitas en imports.
- Los tests en `tests/` siguen `pytest`, un archivo `test_<modulo>.py` por módulo de `src/`.

## Convenciones de documentación (docs/)

- Las entradas de `docs/bitacora/` van una por semana, nombradas `semana-NN.md`.
- No reescribas entradas de bitácora pasadas — son un registro histórico.
- El semáforo de task statements (`docs/semaforo-task-statements.md`) se actualiza,
  no se reescribe desde cero: solo se cambia el estado de los ítems que correspondan.

## Contexto del programa

Certificación objetivo: Claude Certified Architect – Foundations (CCAR-F).
5 dominios: Agentic Architecture (27%), Tool Design & MCP (18%), Claude Code Config (20%),
Prompt Engineering & Structured Output (20%), Context Management & Reliability (15%).
