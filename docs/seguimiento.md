# Seguimiento — CCAR-F (checklist vivo)

Plan de referencia: `plan_certificacion_claude_architect.md`.
Formato: `- [ ]` sin hacer, `- [x]` hecho.
Las "semanas" son solo un envoltorio del contenido: se avanza en orden, sin comprimir nada, y el contenido de una semana puede llevar varias semanas reales. No se mueven actividades entre bloques; solo se marca lo hecho.

## Semana 1 — Bloque 0: Habilitación
- [x] Notebook `Katas_CCAF_Colab.ipynb` en Colab + copia en Drive
- [x] Setup global pasos 1-4
- [x] Repo `ccaf-orquestador-lab` creado y organizado (estructura, evidencias, reflexiones)
- [x] Módulo 1 — Accessing Claude with the API (9/9)
- [x] Módulo 9 — Agents and Workflows
- [x] PDF guía oficial leído hasta sección 4 (además Domain 1, Domain 4 y task statement 2.1)
- [x] API key propia: comprar $5 de crédito en console.anthropic.com y generar la key
- [x] Setup global pasos 5-6 (`ANTHROPIC_API_KEY` como Secret de Colab)

## Semana 2 — Bloque 1, mitad
- [ ] Kata 01 — Bucle Agéntico Determinista
- [ ] Kata 05 — Schemas Defensivos
- [ ] Kata 26 — Validación-Retry
- [ ] Kata 14 — Few-shot para bordes
- [ ] Módulo 4 — Tool use (avance)

## Semana 3 — Bloque 1 completo
- [ ] Kata 16 — Handoff a Humano
- [ ] Kata 21 — Calidad de Descripciones de Tools
- [ ] Kata 30 — Criterios Explícitos
- [ ] Módulo 4 — Tool use (completo)
- [ ] Checkpoint: quiz de 10 preguntas Domain 1 + Domain 4 (al terminar las 7 katas; si va mal en alguna, repetir esa kata antes de avanzar)

## Semana 4 — Bloque 2, mitad
- [ ] Claude Code instalado y autenticado (`claude --version` y `claude -p "responde solo: ok"` funcionan)
- [ ] Curso Claude Code in Action
- [ ] Kata 08 — Memoria Jerárquica
- [ ] Kata 09 — Reglas Condicionales por Ruta
- [ ] Kata 24 — Slash Commands y Skills
- [ ] Kata 02 — PreToolUse
- [ ] Kata 03 — PostToolUse
- [ ] Kata 07 — Plan Mode

## Semana 5 — Bloque 2 completo
- [ ] Módulo 7 — MCP completo (11 lecciones + proyecto `mcp_chat_cli/`)
- [ ] Kata 22 — Config MCP Servers
- [ ] Kata 06 — Errores Estructurados MCP
- [ ] Kata 13 — Code Review Headless CI/CD
- [ ] Kata 23 — Built-in Tools
- [ ] Kata 25 — Gestión de Sesiones
- [ ] Ejercicio 2 (Claude Code end-to-end sobre el repo)
- [ ] Checkpoint: quiz de 10 preguntas Domain 2 + Domain 3

## Semana 6 — Bloque 3, mitad
- [ ] Artículo: How we built our multi-agent research system
- [ ] Artículo: Effective context engineering for AI agents
- [ ] Kata 04 — Aislamiento de Subagentes
- [ ] Kata 28 — Propagación de Errores Multi-Agente
- [ ] Kata 27 — Multi-Pass Review
- [ ] Kata 10 — Prefix Caching
- [ ] Kata 11 — Dilución Softmax
- [ ] Kata 18 — Scratchpad Persistente

## Semana 7 — Bloque 3 completo + Simulacro 1
- [ ] Kata 12 — Prompt Chaining Multi-Pass
- [ ] Kata 15 — Auto-corrección Numérica
- [ ] Kata 20 — Preservación de Provenance
- [ ] Ejercicio 4 (o Ejercicio 1)
- [ ] Checkpoint: quiz de 10 preguntas Domain 1 (multi-agente) + Domain 5
- [ ] Simulacro 1 (30 preguntas, 5 dominios)

## Semana 8 — Repaso, simulacros y examen
- [ ] Repaso dirigido a los 2-3 dominios más débiles según el Simulacro 1
- [ ] Simulacro 2 (30 preguntas) + repaso de "trampas" típicas
- [ ] Simulacro 3 (60 preguntas, 120 min, condiciones reales)
- [ ] Examen agendado en Pearson VUE
- [ ] **Examen CCAR-F rendido** (cuando el Simulacro 3 quede cómodamente sobre 720/1000)

## Opcionales (sin fecha)
- Módulos 2 y 3 (prompt evaluation y prompt engineering)
- Katas 17 (Batches API), 19 (Investigación Adaptativa), 29 (Confidence Calibration)
- Módulos 5 y 6 (RAG y features): fuera del alcance del examen