---
name: analyzing-performance
description: >
  Analyze weekly or monthly content performance metrics for Pato Bichara's LinkedIn and Instagram.
  Takes raw metrics data and produces a structured report with top/worst performers, pillar and
  format analysis, target comparison, and actionable recommendations. Use when Beto needs to
  analyze content metrics, when the user says "analyze this week's performance", "weekly report",
  "how did content perform", or provides metrics data for analysis.
---

# Analyzing Content Performance — Pato Bichara

Analyze content performance metrics to produce weekly or monthly reports that drive data-informed decisions about content strategy. Transforms raw numbers into actionable insights.

## Before Analyzing

1. Read the metrics framework at [references/metrics-framework.md](references/metrics-framework.md)
2. For strategy context, reference `/Users/patobichara/Code/pato-content-strategy/ESTRATEGIA-CONTENIDO.md`

## Input

The user provides one of the following:

- **Weekly metrics:** LinkedIn Analytics export + Instagram Insights for the past week
- **Monthly metrics:** 4+ weeks of data for monthly strategic analysis
- **Partial data:** Whatever metrics are available (skill adapts to what's provided)

Metrics can be provided as:
- Pasted text (table or list)
- CSV data
- Screenshots (describe what you see)
- Partial notes ("this post got 5% engagement, this one got 1.2%")

If data is incomplete, analyze what's available and flag what's missing.

## Workflow

### Step 1: Determine Analysis Type

- **Weekly report** (default): If 1 week of data provided
- **Monthly report**: If 4+ weeks of data provided or user requests monthly analysis
- **Ad hoc**: If user asks about specific posts or a specific question

### Step 2: Parse and Organize Data

Organize the raw data into a structured format:
- Post title/topic
- Date published
- Platform (LinkedIn / Instagram)
- Format (text / carousel / reel / static / story)
- Slot (branded or free, day of week)
- Pillar (1 / 2 / 3 — infer from topic if not provided)
- Key metrics: impressions/reach, engagement rate, comments, shares, saves (IG)

If pillar isn't explicit, infer from the post topic. Flag any uncertain classifications.

### Step 3: Analyze Performance

#### For Weekly Reports:

**3A. Top 3 Performers**
For each top performer (ranked by engagement rate):
- Post title/topic, platform, format
- Engagement rate and key metrics
- Hypothesis: Why did it work? (topic resonance? strong hook? format? timing? trending topic?)

**3B. Worst Performer**
- Post title/topic, platform, format
- Engagement rate and key metrics
- Hypothesis: Why did it underperform? (weak hook? saturated topic? bad timing? wrong format?)
- Lesson: What to avoid or change

**3C. Performance by Dimension**
Generate comparison tables for:
- **By pillar:** Average engagement per pillar vs targets (45/30/25)
- **By format:** Average engagement per format (text, carousel, reel, static)
- **By slot:** Average engagement per day/slot
- **By platform:** LinkedIn vs Instagram overall

**3D. Targets vs Actual**
- LinkedIn engagement rate: actual vs >3% target
- Instagram engagement rate: actual vs >5% target
- Comments: actual vs targets (>15 LinkedIn, >10 Instagram)
- Pillar distribution: actual % vs target % (flag if any pillar is >5% off target)

**3E. Business Metrics**
If provided:
- DMs with commercial interest
- Leads attributable to content
- Invitations (panels, podcasts, conferences)
- Notable mentions or reposts

**3F. Recommendations**
3-5 specific, data-backed actions for the next week. Each recommendation must:
- Reference specific data from this analysis
- Be actionable (not "post better content")
- Follow format: "Do [action] because [data-backed reason]"

#### For Monthly Reports (additional sections):

**3G. Trends Over Time**
- Engagement trend by week (improving, declining, stable)
- Audience growth trend
- Best and worst weeks with hypotheses

**3H. Thematic Patterns**
- Topics with consistently high engagement
- Topics with diminishing returns (overused)
- Content gaps (pillar/topic areas with few posts)

**3I. Branded vs Free Slots**
- Average engagement: branded slots (#FrasesBienCollective, #JuevesCollective, #ViernesDeLibrosParaLideres) vs free slots (Tue/Wed)
- Which branded slot performs best?
- Should slot structure change?

**3J. Instagram Deep Dive**
- Which format dominates? (Reel vs carousel vs static)
- Save rate (key IG metric)
- Cross-platform comparison: same content on LinkedIn vs Instagram

**3K. Strategic Recommendations**
5 strategic adjustments for the next month, ranked by expected impact.

### Step 4: Output

#### Weekly Report Format:

```
## Weekly Performance Report: [Date Range]

**Posts analyzed:** [X LinkedIn + Y Instagram]
**Overall engagement:** [LinkedIn avg% vs 3% target | Instagram avg% vs 5% target]

---

### Resumen Ejecutivo

[2-3 sentences: highlight, lowlight, and one key insight from the week]

---

### Top 3 Performers

**#1: [Post title/topic]**
- Platform: [LinkedIn/Instagram] | Format: [text/carousel/reel]
- Engagement: [X%] | Comments: [X] | [Shares/Saves: X]
- Why it worked: [1-2 sentences]

**#2: [Post title/topic]**
- Platform: [LinkedIn/Instagram] | Format: [text/carousel/reel]
- Engagement: [X%] | Comments: [X] | [Shares/Saves: X]
- Why it worked: [1-2 sentences]

**#3: [Post title/topic]**
- Platform: [LinkedIn/Instagram] | Format: [text/carousel/reel]
- Engagement: [X%] | Comments: [X] | [Shares/Saves: X]
- Why it worked: [1-2 sentences]

---

### Worst Performer

**[Post title/topic]**
- Platform: [LinkedIn/Instagram] | Format: [text/carousel/reel]
- Engagement: [X%] | Comments: [X]
- Why it underperformed: [1-2 sentences]
- Lesson: [1 sentence]

---

### Performance por Dimensiones

**Por Pilar:**
| Pilar | Posts | Avg Engagement | Target | Status |
|-------|-------|---------------|--------|--------|
| 1: Liderazgo/AI | X | X% | 45% share | [On/Off target] |
| 2: Talento/Cultura | X | X% | 30% share | [On/Off target] |
| 3: Futuro del Trabajo | X | X% | 25% share | [On/Off target] |

**Por Formato:**
| Formato | Posts | Avg Engagement |
|---------|-------|---------------|
| [format] | X | X% |

**Por Slot:**
| Dia | Slot | Avg Engagement |
|-----|------|---------------|
| Lunes | #FrasesBienCollective | X% |
| Martes | Tema libre | X% |
| ... | ... | ... |

---

### Targets vs Actual

| Metrica | Target | Actual | Status |
|---------|--------|--------|--------|
| LinkedIn engagement | >3% | X% | [Met/Not met] |
| Instagram engagement | >5% | X% | [Met/Not met] |
| LinkedIn comments | >15 | X avg | [Met/Not met] |
| Instagram comments | >10 | X avg | [Met/Not met] |

---

### Business Metrics

- DMs comerciales: [X]
- Leads: [X]
- Invitaciones: [X]
- Menciones relevantes: [X]

---

### Recomendaciones para la Proxima Semana

1. **[Accion]** — Porque [razon basada en datos de este reporte]
2. **[Accion]** — Porque [razon basada en datos de este reporte]
3. **[Accion]** — Porque [razon basada en datos de este reporte]

---

**Notas para Beto:**
- [Data gaps or caveats]
- [Metrics that need manual verification]
- [Questions for Pato based on the data]
```

## Guidelines

- **Data first, opinions second.** Every recommendation must be backed by a number from this report. No "I think" — only "The data shows."
- **Hypotheses, not conclusions.** When explaining why a post performed well or poorly, frame it as a hypothesis ("This may have performed well because...") — correlation is not causation.
- **Actionable > interesting.** A fascinating insight that doesn't lead to a clear action is less valuable than a simple observation with an obvious next step.
- **Flag data gaps.** If data is incomplete or metrics seem off, flag it. Don't analyze bad data as if it were good.
- **Context matters.** A 2% engagement on a post about a niche topic might be fine; a 2% on a viral-ready topic is underperformance. Factor in topic difficulty.
- **No pedir aclaraciones.** Analyze what's available. Note what's missing in "Notas para Beto."
