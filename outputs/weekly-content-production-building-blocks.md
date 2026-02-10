# AI Building Block Map: Weekly Content Production

## Scenario Summary

**Workflow Name:** Weekly Content Production
**Type:** Augmented (transicion de Manual a Augmented)
**Team:** Pato Bichara (aprobacion, engagement, ideas) + Beto (produccion, operacion)
**Platforms:** LinkedIn (5 posts/semana) + Instagram (2-3 posts/semana + Stories diarios)

---

## Mapa de Autonomia por Workflow

| FT | Workflow | Owner Actual | Tipo Actual | Tipo Propuesto | AI Building Block | Ahorro Estimado |
|----|----------|-------------|-------------|----------------|-------------------|----------------|
| **FASE 1: CAPTURA** |
| FT-01 | Captura de Ideas Organicas | Pato → Beto | Manual | Manual | Ninguno (proceso humano por naturaleza) | — |
| FT-02 | Investigacion y Propuesta Proactiva | Beto | Manual | AI-Semi-Autonomous | **Skill**: Trend Scanner + Topic Proposer | 1-2 hrs/sem |
| **FASE 2: DESARROLLO** |
| FT-03 | Extraccion de Frase Memorable | Beto | Manual | AI-Semi-Autonomous | **Skill**: Transcript Analyzer (extrae frases clave) | 30-45 min/sem |
| FT-04 | Diseno de Post de Frase | Beto | Manual | AI-Semi-Autonomous | **Skill**: Draft Post from Quote | 30-45 min/sem |
| FT-05 | Extraccion de Insight de Sesion | Beto | Manual | AI-Semi-Autonomous | **Skill**: Transcript Analyzer (extrae insight central) | 45-60 min/sem |
| FT-06 | Desarrollo de Narrativa de Sesion | Beto | Manual | AI-Semi-Autonomous | **Skill**: Draft Narrative Post | 30-45 min/sem |
| FT-07 | Seleccion de Libro desde Backlog | Beto | Manual | AI-Deterministic | **Prompt**: Book Selector (filtra backlog, prioriza recientes, evita repetidos) | 15 min/sem |
| FT-08 | Desarrollo de Recomendacion de Libro | Beto | Manual | AI-Semi-Autonomous | **Skill**: Draft Book Review (input: Readwise highlights) | 30-45 min/sem |
| FT-09 | Desarrollo de Post Tematico Libre | Beto | Manual | AI-Semi-Autonomous | **Skill**: Draft Thematic Post (investigacion + drafting) | 1-2 hrs/sem (x2 posts) |
| **FASE 3: CONSOLIDACION** |
| FT-10 | Consolidacion de Propuestas | Beto | Manual | AI-Deterministic | **Prompt**: Weekly Review Checklist (verifica balance pilares, redundancia) | 15-20 min/sem |
| FT-11 | Revision y Aprobacion | Pato | Manual | Human [NO-DELEGABLE] | **Prompt**: Pre-Review QA (AI pre-checa antes de que Pato revise) | 10-15 min/sem |
| **FASE 4: PUBLICACION** |
| FT-12 | Publicacion en LinkedIn | Beto | Manual | Manual o MCP | **MCP**: Scheduling tool (si existe API) | 15-20 min/sem |
| FT-16 | Adaptacion a Instagram [NUEVO] | Beto | — | AI-Semi-Autonomous | **Skill**: Repurpose LinkedIn to Instagram | 1-1.5 hrs/sem |
| FT-17 | Stories de Instagram [NUEVO] | Pato + Beto | — | Manual (Pato) + AI-Deterministic (Beto) | **Prompt**: Story Ideas Generator | 15-20 min/sem |
| **FASE 5: ENGAGEMENT** |
| FT-13 | Engagement y Respuestas | Pato | Manual | Human + AI Assist [NO-DELEGABLE] | **Prompt**: Response Drafter (Pato revisa antes de enviar) | 30-45 min/sem |
| FT-14 | Tracking de Metricas | Beto | Manual | AI-Semi-Autonomous | **Skill**: Performance Analyzer | 30-45 min/sem |
| FT-15 | Analisis y Ajuste Estrategico | Pato + Beto | Manual | AI-Semi-Autonomous | **Skill**: Monthly Strategy Review | 30-45 min/mes |

---

## Resumen de Autonomia

| Clasificacion | Workflows | Notas |
|--------------|-----------|-------|
| **Human (no-delegable)** | FT-01, FT-11, FT-13 | La autenticidad y el juicio estrategico de Pato son la ventaja competitiva |
| **AI-Deterministic** | FT-07, FT-10, FT-12 | Reglas claras, poco juicio necesario |
| **AI-Semi-Autonomous** | FT-02, 03, 04, 05, 06, 08, 09, 14, 15, 16 | AI hace el heavy lifting, Beto/Pato refina |
| **Fully Autonomous** | Ninguno | El contenido requiere voz autentica — automatizacion total dañaria la marca |

---

## AI Building Blocks Recomendados

### SKILLS (reutilizables, alta frecuencia)

#### 1. Skill: "Analyze Session Transcript"
**Usado por:** FT-03 + FT-05 (dos pajaros de un tiro)
**Input:** Transcript o presentacion de sesion Collective
**Context:** Brief de voz de Pato, ejemplos de frases memorables pasadas, estrategia de contenido
**Output:**
- Top 3 frases memorables con contexto (para FT-03 → FT-04, slot lunes)
- Insight central + angulo narrativo sugerido (para FT-05 → FT-06, slot jueves)
**Prioridad:** ALTA — ahorra 1-1.5 hrs/semana y mejora la calidad de extraccion

#### 2. Skill: "Draft Content Post"
**Usado por:** FT-04, FT-06, FT-09 (adapta segun tipo)
**Input:** Tipo de post (frase/narrativa/tematico) + materia prima (frase, insight, idea)
**Context:** Brief de voz de Pato, estrategia de contenido, ejemplos de posts exitosos, hashtags branded
**Output:** Draft completo con estructura Hook → Contexto → Insight → CTA + hashtags + nota de visual sugerido
**Variantes:**
- `type: quote` → FT-04 (post de frase #FrasesBienCollective)
- `type: narrative` → FT-06 (narrativa de sesion #JuevesCollective)
- `type: thematic` → FT-09 (post tematico libre)
**Prioridad:** ALTA — ahorra 2-3 hrs/semana en drafting

#### 3. Skill: "Draft Book Recommendation"
**Usado por:** FT-08
**Input:** Titulo del libro + highlights de Readwise
**Context:** Brief de voz de Pato, angulo de liderazgo, ejemplos de recomendaciones pasadas
**Output:** Draft de recomendacion con estructura Hook → Por que → 3 ideas clave → Para quien → CTA + #ViernesDeLibrosParaLideres
**Prioridad:** MEDIA — ahorra 30-45 min/semana, alto valor por consistencia

#### 4. Skill: "Repurpose LinkedIn to Instagram"
**Usado por:** FT-16
**Input:** Post de LinkedIn aprobado (texto + visual)
**Context:** Guias de tono Instagram (mas corto, conversacional), formatos Instagram
**Output:**
- Caption adaptada (50-70% del largo original, mas conversacional)
- Sugerencia de formato (Reel, carrusel, estatico)
- Script de Reel (si aplica, 30-60 seg)
**Prioridad:** ALTA — habilita Instagram sin duplicar esfuerzo

#### 5. Skill: "Analyze Weekly Performance"
**Usado por:** FT-14
**Input:** Metricas de la semana (LinkedIn + Instagram, pegadas o CSV)
**Context:** Targets (>3% LinkedIn, >5% Instagram), distribucion de pilares, historico
**Output:** Reporte semanal (top/worst performers, patrones, recomendaciones, metricas de negocio)
**Prioridad:** MEDIA — ahorra 30-45 min/semana, mejora decision-making

#### 6. Skill: "Research and Propose Topics"
**Usado por:** FT-02
**Input:** Pilares con gaps, tendencias actuales, solicitudes internas
**Context:** Estrategia de contenido, performance reciente, calendario de Collective
**Output:** 3-5 propuestas de temas con angulo, pilar, y slot recomendado
**Prioridad:** MEDIA — ahorra 1-2 hrs/semana, mejora proactividad

### PROMPTS (uso ad hoc, menor frecuencia)

#### 7. Prompt: "Pre-Review QA"
**Usado por:** FT-10/FT-11
**Funcion:** Antes de que Pato revise, AI verifica: balance de pilares, redundancia, hashtags correctos, tono consistente, CTAs claros
**Prioridad:** BAJA — ahorra 10-15 min/sem pero reduce fricci0n de revision

#### 8. Prompt: "Response Drafter"
**Usado por:** FT-13
**Funcion:** Dado un comentario y contexto del post, AI drafta una respuesta en voz de Pato (Pato revisa antes de enviar)
**Prioridad:** MEDIA — ahorra 30-45 min/sem en engagement

#### 9. Prompt: "Story Ideas Generator"
**Usado por:** FT-17
**Funcion:** Genera ideas de Stories para la semana basadas en contenido publicado, eventos, y calendario
**Prioridad:** BAJA — Stories son mayormente espontaneos

### CONTEXT (proyecto o archivos de referencia)

#### 10. Claude Project: "Pato Content Production"
**Pre-cargar:**
- Estrategia de contenido (ESTRATEGIA-CONTENIDO.md)
- Brief de voz de Pato (needs formalization)
- Datos de Collective Academy
- Ejemplos de posts exitosos (Voice & Story Library)
- Hashtags branded y guias de formato
**Prioridad:** CRITICA — todos los Skills y Prompts dependen de este contexto

---

## Human-in-the-Loop Gates

### Gate 1: Aprobacion de Contenido (FT-11) [NO-DELEGABLE]
**Quien:** Pato
**Por que:** Content = marca personal. Solo Pato sabe que suena autentico.
**Que revisar:** Tono, precision de historias, riesgo reputacional, alineacion de CTA

### Gate 2: Engagement (FT-13) [NO-DELEGABLE]
**Quien:** Pato
**Por que:** Relaciones de alto valor se construyen en las respuestas, no en los posts.
**Que revisar:** AI puede draftear respuestas, pero Pato las envia.

### Gate 3: Decision Estrategica (FT-15)
**Quien:** Pato + Beto
**Por que:** Solo Pato tiene el contexto completo de negocio (prioridades Collective, mercado, bandwidth personal).

---

## Ahorro de Tiempo Estimado

### Estado Actual (Manual)
| Rol | Horas/Semana |
|-----|-------------|
| Beto | 10-15 hrs |
| Pato | 3-4 hrs |
| **Total** | **13-19 hrs** |

### Estado Propuesto (Augmented con AI)
| Rol | Horas/Semana | Ahorro |
|-----|-------------|--------|
| Beto | 5-8 hrs | 5-7 hrs (-50%) |
| Pato | 2.5-3.5 hrs | 0.5-1 hr (-15%) |
| **Total** | **7.5-11.5 hrs** | **5.5-7.5 hrs (-40%)** |

**Nota:** El ahorro de Pato es menor porque sus workflows (FT-11, FT-13) son no-delegables por diseño. El mayor ahorro es en tiempo de Beto, quien puede redirigir ese tiempo a otras iniciativas o a mejorar calidad.

### Bonus: Instagram sin costo incremental significativo
Con el Skill de repurposing (FT-16), Instagram se agrega con ~1-2 hrs/semana adicionales de Beto, no 5-8 hrs que tomaria crear contenido original.

---

## Orden de Implementacion Recomendado

### Fase 1: Quick Wins (Semana 1-2)
**Construir:**
1. Claude Project con contexto base (estrategia, voz, datos)
2. Skill: "Draft Content Post" (FT-04, 06, 09) — mayor ahorro inmediato
3. Skill: "Repurpose LinkedIn to Instagram" (FT-16) — habilita nuevo canal

**ROI:** Ahorra 3-4 hrs/semana de Beto + habilita Instagram
**Riesgo:** Bajo — Pato sigue aprobando todo

### Fase 2: Automatizacion de Extraccion (Semana 3-4)
**Construir:**
4. Skill: "Analyze Session Transcript" (FT-03, 05) — requiere acceso a transcripts
5. Skill: "Draft Book Recommendation" (FT-08) — requiere acceso a Readwise

**ROI:** Ahorra 1.5-2 hrs/semana de Beto
**Requisito:** Acceso sistematico a transcripts de sesiones y Readwise API

### Fase 3: Inteligencia y Optimizacion (Mes 2+)
**Construir:**
6. Skill: "Analyze Weekly Performance" (FT-14)
7. Skill: "Research and Propose Topics" (FT-02)
8. Prompt: "Pre-Review QA" (FT-10/11)

**ROI:** Mejora decision-making, ahorra 1-2 hrs/semana
**Requisito:** 4+ semanas de datos historicos para que el analisis sea significativo

### Fase 4: Refinamiento (Mes 3+)
**Construir:**
9. Prompt: "Response Drafter" (FT-13)
10. Explorar MCP de scheduling (FT-12)
11. Prompt: "Story Ideas Generator" (FT-17)

**ROI:** Marginal en tiempo, alto en reduccion de friccion
