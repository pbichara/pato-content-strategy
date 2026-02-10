# Pato Bichara — Content Strategy & AI Production System

Sistema de produccion de contenido para Pato Bichara, CEO de [Collective Academy](https://collective.academy), con skills de Claude Code que automatizan el workflow semanal de LinkedIn e Instagram.

## Contexto

Pato publica 5 posts/semana en LinkedIn (slots branded + tematicos) y 2-3 posts/semana en Instagram, posicionandose como lider de opinion en liderazgo empresarial y transformacion con AI en Latinoamerica.

**Equipo:**
- **Pato** — Aprobacion de contenido, engagement, ideas (no-delegable)
- **Beto** — Produccion, operaciones, drafting, publicacion, tracking

**Antes de AI:** 13-19 hrs/semana entre los dos. **Con AI:** 7.5-11.5 hrs/semana (~40% de reduccion, mayormente en tiempo de Beto).

---

## Estructura del Repositorio

```
pato-content-strategy/
├── ESTRATEGIA-CONTENIDO.md          # Estrategia maestra de contenido
├── .claude-plugin/plugin.json        # Plugin local para Claude Code
├── outputs/
│   ├── weekly-content-production-definition.md    # 17 workflows (FT-01 a FT-17)
│   ├── weekly-content-production-building-blocks.md  # Mapa de building blocks AI
│   └── weekly-content-production-prompt.md        # Prompt baseline del workflow
└── skills/
    ├── drafting-content-posts/        # Fase 1 — Draft LinkedIn posts
    ├── repurposing-to-instagram/      # Fase 1 — Adaptar LinkedIn → Instagram
    ├── analyzing-session-transcripts/ # Fase 2 — Extraer frases + insights
    ├── drafting-book-recommendations/ # Fase 2 — Posts de libros (#ViernesDeLibros)
    ├── analyzing-performance/         # Fase 3 — Reporte semanal de metricas
    └── researching-topics/            # Fase 3 — Proponer temas para slots libres
```

---

## Pilares de Contenido

| Pilar | Peso | Temas |
|-------|------|-------|
| 1: Liderazgo y Estrategia en la Era de AI | 45% | AI, frameworks de decision, modelos mentales, trade-offs estrategicos |
| 2: Desarrollo de Talento y Cultura | 30% | Cultura organizacional, multiplicador de exito, lecciones de Collective |
| 3: Futuro del Trabajo | 25% | Habilidades del futuro, nuevos modelos de carrera, brecha universidad-mercado |

**Lente transversal:** Perspectiva LatAm en todo el contenido.

---

## Calendario Semanal — LinkedIn

| Dia | Slot | Hashtag | Fuente |
|-----|------|---------|--------|
| Lunes | Frase memorable | #FrasesBienCollective | Sesiones Collective |
| Martes | Tema libre | Tematicos | Ideas Pato / Investigacion Beto |
| Miercoles | Tema libre | Tematicos | Ideas Pato / Investigacion Beto |
| Jueves | Insight de sesion | #JuevesCollective | Transcript de sesion |
| Viernes | Recomendacion de libro | #ViernesDeLibrosParaLideres | Readwise + backlog |

---

## Skills de Claude Code

Cada skill vive en `skills/[nombre]/SKILL.md` con un subdirectorio `references/` de archivos de soporte. Beto los invoca durante la produccion batch semanal — pega el input, obtiene output completo.

### Fase 1 — Quick Wins

| Skill | Workflow | Que hace |
|-------|----------|----------|
| `drafting-content-posts` | FT-04, FT-06, FT-09 | Draftea posts de LinkedIn para 3 tipos: `quote` (lunes), `narrative` (jueves), `thematic` (martes/miercoles). Output listo para copiar y pegar. |
| `repurposing-to-instagram` | FT-16 | Adapta un post aprobado de LinkedIn para Instagram. Recomienda formato (Reel/carrusel/estatico), adapta caption, genera script o breakdown, y sugiere hashtags. |

### Fase 2 — Extraccion de Contenido

| Skill | Workflow | Que hace |
|-------|----------|----------|
| `analyzing-session-transcripts` | FT-03, FT-05 | Analiza transcripts de sesiones Collective y extrae: top 3 frases memorables (para lunes) + insight central con angulo narrativo (para jueves) + oportunidades bonus. |
| `drafting-book-recommendations` | FT-08 | Draftea el post de viernes #ViernesDeLibrosParaLideres a partir del titulo del libro y highlights de Readwise. Tono conversacional, como recomendar un libro tomando un cafe. |

### Fase 3 — Inteligencia y Optimizacion

| Skill | Workflow | Que hace |
|-------|----------|----------|
| `analyzing-performance` | FT-14 | Analiza metricas semanales/mensuales (LinkedIn + Instagram). Genera reporte con top/worst performers, analisis por pilar/formato/slot, targets vs actual, y recomendaciones accionables. |
| `researching-topics` | FT-02 | Propone 3-5 temas para slots libres (martes/miercoles) con angulo diferenciado, hook sugerido, y balance de pilares. Prioriza temas donde Pato tiene ventaja unica. |

---

## Workflow de Produccion Semanal

El workflow completo tiene 17 pasos (FT-01 a FT-17), documentados en `outputs/weekly-content-production-definition.md`. El flujo simplificado:

```
Domingo     → Planificacion semanal (Beto)
Lun-Mar     → Produccion batch:
                1. Analizar transcript de sesion → frases + insight
                2. Draftear posts (quote, narrative, thematic, libro)
                3. Revisar balance de pilares
                4. Adaptar 2-3 posts para Instagram
Martes      → Pato revisa y aprueba (NO-DELEGABLE)
Mar-Vie     → Publicacion (Beto)
Diario      → Engagement 15-20 min (Pato, NO-DELEGABLE)
Viernes     → Tracking de metricas + reporte (Beto + AI)
```

---

## Como Usar los Skills

### Ejemplo: Draftear un post de frase (lunes)

```
Analiza este transcript de la sesion de Collective y extrae las frases memorables:

[pegar transcript]
```

Luego, con la frase seleccionada:

```
Draft a quote post for #FrasesBienCollective usando esta frase:

"La velocidad mata menos empresas que la indecision"
- Speaker: Pato Bichara
- Contexto: Sesion de estrategia con CEOs, discutiendo parálisis por analisis
```

### Ejemplo: Reporte semanal de performance

```
Analiza las metricas de esta semana:

LinkedIn:
- Lunes (frase): 4.2% engagement, 23 comentarios
- Martes (AI en hiring): 2.8% engagement, 12 comentarios
- Miercoles (cultura): 5.1% engagement, 31 comentarios
- Jueves (insight): 3.5% engagement, 18 comentarios
- Viernes (libro): 3.0% engagement, 15 comentarios

Instagram:
- Carrusel AI: 6.2% engagement, 45 saves
- Reel cultura: 8.1% engagement, 12 comentarios
```

### Ejemplo: Proponer temas

```
Propone temas para martes y miercoles de la proxima semana. Esta semana publicamos mucho Pilar 1 (AI). Necesitamos mas Pilar 2 (Talento) y Pilar 3 (Futuro del Trabajo).
```

---

## Notion Integration

Todo esta trackeado en el [AI Operations Registry](https://www.notion.so/2fb7fa62343c8105a78cc7a9e233de3f) de Notion:

- **Workflows DB** — 17 workflows (FT-01 a FT-17) con tipo (Manual/Augmented), trigger, y outcome
- **AI Assets DB** — 6 skills registrados con descripcion, quick start prompt, y link a GitHub
- **Business Process** — Content Marketing como proceso padre

---

## Targets

| Metrica | LinkedIn | Instagram |
|---------|----------|-----------|
| Engagement rate | >3% | >5% |
| Comentarios/post | >15 | >10 |
| Frecuencia | 5 posts/semana | 2-3 posts/semana + Stories diarios |
| Pillar distribution | 45% / 30% / 25% | Same |

---

## Fases de Implementacion

- [x] **Fase 1:** Drafting de posts + Repurposing a Instagram
- [x] **Fase 2:** Analisis de transcripts + Recomendaciones de libros
- [x] **Fase 3:** Analisis de performance + Investigacion de temas
- [ ] **Fase 4:** Response Drafter + Story Ideas + Pre-Review QA + scheduling MCP

---

## Voz y Tono

Detallado en `skills/drafting-content-posts/references/voice-guidelines.md`. Resumen:

- **60%** Educativo-practico — Frameworks accionables, datos + experiencia
- **25%** Conversacional-autentico — Historias personales, vulnerabilidad estrategica
- **15%** Profesional-inspirador — Vision de LatAm, celebrar logros

**Reglas no negociables:** Nunca predicar. Siempre con evidencia. Accesible sin ser simplista. Espanol por defecto.
