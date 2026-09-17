# Plan Autónomo — Claude Certified Architect (Foundations) — CCAR-F

**Modalidad: 100% autodidacta.** No estás inscrito en el programa formal Orquestador CCAF de Sofka — tienes acceso a sus materiales escritos (guía, katas, notebook, exam guide) pero no a las sesiones en vivo, ni hay grupo, fechas límite de cohorte, ni entregables que enviar a nadie. Este plan reemplaza al anterior, que asumía por error que ibas a asistir a "Sesiones" guiadas.

**Lo que se mantiene (es tuyo, no depende de la cohorte):**
- Las 30 katas del notebook `Katas_CCAF_Colab.ipynb`
- El curso gratuito `Building with the Claude API` en `academy.claude.com`
- Los 4 ejercicios integradores de la guía oficial del examen (PDF, sección 8)
- Tu repo `ccaf-orquestador-lab` con bitácora
- El blueprint de 5 dominios y 30 task statements del examen CCAR-F

**Lo que se elimina (era exclusivo de la cohorte formal):**
- Las 6 "Sesiones" guiadas en vivo y sus prerrequisitos duros
- Entregables "al grupo del programa"
- El plazo de agendar el examen "antes de fin de Semana 3"
- Las Semanas 5-6 (ASDD y evaluación organizacional) — contenido que solo se define y entrega en vivo a la cohorte

**Calendario: 8 semanas (~2 meses), con fecha de examen objetivo.** No es opcional tener un cierre — el objetivo es la certificación, no "estudiar sin fin". Estimé ~48h de contenido total (katas + cursos + ejercicios + simulacros) repartidas en los 4 Bloques. A ~6h/semana reales con tu ritmo de ~1:30h/día variable, esto cierra en 8 semanas.

| Semana | Fechas | Qué debe estar cerrado al final |
|---|---|---|
| 1 | 15-21 sept | Bloque 0 completo (Módulos 1 y 9, PDF hasta sección 4, API key propia con crédito) |
| 2 | 22-28 sept | Bloque 1, mitad (katas 01/05/26/14 + avance Módulo 4) |
| 3 | 29 sept-5 oct | Bloque 1 completo (katas 16/21/30 + checkpoint Domain 1/4) |
| 4 | 6-12 oct | Bloque 2, mitad (Claude Code instalado, katas 08/09/24/02/03/07) |
| 5 | 13-19 oct | Bloque 2 completo (katas 22/06/13/23/25 + Módulo MCP + Ejercicio 2 + checkpoint) |
| 6 | 20-26 oct | Bloque 3, mitad (katas 04/28/27/10/11/18) |
| 7 | 27 oct-2 nov | Bloque 3 completo (katas 12/15/20 + Ejercicio + checkpoint) + Simulacro 1 |
| 8 | 3-9 nov | Repaso dirigido + Simulacro 2 + Simulacro 3 + **examen agendado y rendido esta semana** (objetivo: viernes 6 o sábado 7 de nov) |

**Regla de ajuste — para que esto no se desvíe:** revisamos el avance cada semana (dime cómo vas y actualizamos). Podés moverte ±2-3 días dentro de una semana sin drama. Pero si una semana completa se atrasa (por ejemplo, llegás al domingo sin cerrar lo de esa fila), no dejamos que la fecha final "flote" en silencio — lo hablamos explícitamente ahí mismo y decidimos juntos: comprimir contenido de las semanas que quedan, o correr la fecha de examen un número concreto de días (nunca de forma indefinida).

---

## Mapa de `recursos-curso-api/` (sin cambios)

| Carpeta | Cuándo | ¿Entra en el examen? |
|---|---|---|
| `modulo-01-accessing-the-api/` | Bloque 0 | Sí |
| `modulo-09-agents-workflows/` | Bloque 0 | Sí |
| `modulo-04-tool-use/` | Bloque 1 | Sí, prioritario |
| `modulo-02-prompt-evaluation/`, `modulo-03-prompt-engineering/` | Bloque 1 (opcional) | Parcial |
| `modulo-07-mcp/` | Bloque 2 | Sí, prioritario |
| `modulo-05-rag/`, `modulo-06-features/` | Cuando quieras, sin apuro | No — fuera de alcance del examen |

---

## BLOQUE 0 — Habilitación (~3h, ya en curso)

**Objetivo:** entorno operativo + primer contacto con el material. Sin fechas duras, pero es lo lógico para arrancar.

- [x] Notebook subido a Colab, copia guardada en Drive
- [x] Setup global pasos 1-4 ejecutados
- [x] Repo `ccaf-orquestador-lab` creado con estructura de práctica + documentación
- [ ] Módulo 1 (Accessing Claude with the API) — **en progreso, lección 6 de 9**
- [ ] Módulo 9 (Agents and Workflows)
- [ ] Leer el PDF de la guía oficial hasta la sección 4 (blueprint de dominios)
- [ ] Decidir si compras los $5 de crédito en `console.anthropic.com` para tu propia API key de práctica (opcional — no es necesario para las katas, esas se autentican distinto)

**Sobre la API key de las katas:** en el programa formal, la entregaban en la "Sesión 1". Como no estás inscrito, vas a necesitar tu **propia** key de `console.anthropic.com` (con los $5 mínimos de crédito) para correr los pasos 5-6 del Setup global y ejecutar las katas de verdad. No hay atajo para esto — sin key propia, puedes leer el código de las katas pero no ejecutarlo.

---

## BLOQUE 1 — Fundamentos: loop agéntico, tool use, structured output (Semanas 2-3, 22 sept-5 oct)
*Domain 1 (parcial) + Domain 4 completo — ~47% del examen entre los dos.*

Sin sesión que prepare esto — vas directo a las katas con el contexto que ya tengas del Módulo 1 y 4.

**Katas a resolver (con tu propia API key ya cargada):**
- **01** — Bucle Agéntico Determinista
- **05** — Schemas Defensivos (extracción estructurada)
- **26** — Validación-Retry
- **14** — Few-shot para bordes
- **16** — Handoff a Humano
- **21** — Calidad de Descripciones de Tools
- **30** — Criterios Explícitos

**Curso:** `modulo-04-tool-use/` completo. Opcional: `modulo-02` y `modulo-03`.

**Checkpoint de autoevaluación:** cuando termines las 7 katas, pídeme un quiz de 10 preguntas mezclando Domain 1 y Domain 4. Si te va mal en alguna, no sigas — repite la kata correspondiente antes de avanzar.

---

## BLOQUE 2 — Claude Code y MCP (Semanas 4-5, 6-19 oct)
*Domain 3 (20%) + Domain 2 (18%) — 38% del examen.*

**Requisito real (no de cohorte, sino técnico):** instala y autentica Claude Code antes de empezar — `claude --version` y `claude -p "responde solo: ok"` deben funcionar. Usa tu repo `ccaf-orquestador-lab` como terreno de práctica.

**Curso:** `Claude Code in Action` (curso corto y gratuito, complementario al de la API) + `modulo-07-mcp/` completo (11 lecciones + proyecto `mcp_chat_cli/`).

**Katas a resolver, sobre tu repo real:**
- **08** — Memoria Jerárquica (CLAUDE.md)
- **09** — Reglas Condicionales por Ruta
- **24** — Slash Commands y Skills
- **02** — Bloqueo determinista `PreToolUse`
- **03** — `PostToolUse`
- **07** — Plan Mode
- **22** — Config de MCP Servers
- **06** — Errores Estructurados MCP
- **13** — Code Review Headless CI/CD
- **23** — Built-in Tools
- **25** — Gestión de Sesiones

Es más contenido que el Bloque 1 — repártelo en 2-3 semanas sin culpa.

**Ejercicio integrador:** Ejercicio 2 de la guía oficial (Claude Code end-to-end sobre tu repo).

**Checkpoint:** quiz de 10 preguntas Domain 2 + Domain 3.

---

## BLOQUE 3 — Multi-agente, contexto y confiabilidad (Semanas 6-7, 20 oct-2 nov)
*Resto de Domain 1 + Domain 5 completo (15%).*

**Lectura recomendada antes de las katas** (artículos públicos de Anthropic, gratuitos):
- *How we built our multi-agent research system* (anthropic.com/engineering)
- *Effective context engineering for AI agents* (mismo blog)

**Katas:**
- **04** — Aislamiento de Subagentes
- **28** — Propagación de Errores Multi-Agente
- **27** — Multi-Pass Review
- **10** — Prefix Caching
- **11** — Dilución Softmax
- **18** — Scratchpad Persistente
- **12** — Prompt Chaining Multi-Pass
- **15** — Auto-corrección Numérica
- **20** — Preservación de Provenance
- Refuerzo opcional: **17** (Batches API), **19** (Investigación Adaptativa), **29** (Confidence Calibration)

**Ejercicio integrador:** Ejercicio 4 (pipeline multi-agente) o Ejercicio 1 (agente con escalación) — elige el que más te falte reforzar.

**Checkpoint:** quiz de 10 preguntas Domain 1 (parte multi-agente) + Domain 5.

---

## BLOQUE 4 — Simulacros y examen (Semanas 7-8, 27 oct-9 nov)

**Semana 7 (27 oct-2 nov), al cerrar el Bloque 3:**
- Simulacro 1: 30 preguntas mezclando los 5 dominios, corregido con explicación de cada distractor.

**Semana 8 (3-9 nov):**
- Lunes-martes: repaso dirigido a tus 2-3 dominios más débiles según el Simulacro 1.
- Miércoles: Simulacro 2 (30 preguntas nuevas) + repaso de "trampas" típicas.
- Jueves: Simulacro 3 completo (60 preguntas, 120 min, condiciones reales).
- Viernes 6 o sábado 7 de nov: **examen real**, si el Simulacro 3 te dio un resultado cómodo por encima del corte (720/1000). Si no, esta es la semana donde hablamos de correr la fecha unos días — no de dejarla flotando.

**Registro:** `anthropic-partners.skilljar.com` o el enlace vigente de Anthropic Partner Academy — como no estás en el programa de Sofka, revisa si necesitas algún código de partner/descuento o si pagas la tarifa estándar de $125 USD directamente.

**Nota sobre el descuento de nómina:** esa cláusula (si repruebas, se descuentan $125 de tu sueldo) era específica del programa formal de Sofka. Al no estar inscrito, probablemente no aplica en tu caso — pero confírmalo con tu empresa si de todas formas usan un canal corporativo para pagar el examen.

---

## Lo que ya no aparece en tu plan (y por qué)

- **Semanas 5-6 (ASDD, evaluación organizacional):** contenido que solo se define y entrega en vivo a la cohorte del programa. Si en algún momento te inscribes formalmente, retómalo entonces — por ahora no es parte de tu ruta.
- **"Sesión guía" y sus preguntas guía:** eran para preparar una discusión en vivo que no vas a tener. Si quieres, puedo seguir usando esas preguntas como ejercicios de reflexión personal (te las hago yo, revisamos tu respuesta juntos) — solo dímelo.

---

## Repo y bitácora — sigue igual

`ccaf-orquestador-lab/` sigue siendo tu sistema de registro. Solo ajusta el lenguaje de las entradas de bitácora: en vez de "Sesión N", usa "Bloque N" o directamente la fecha. El resto (comandos ejecutados, preguntas/aclaraciones, pendientes) se mantiene igual.

## Cómo sigo ayudándote

- "Quiz de la kata [N]" o "quiz de [dominio]" → preguntas estilo examen con explicación.
- "Revísame mi código de la kata [N]" → feedback antes de darla por completa.
- "Hazme la pregunta de reflexión de [tema]" → si quieres mantener ese hábito del programa formal, sin necesidad de entregarla a nadie.
- "Simulacro de N preguntas" → práctica cronometrada.
