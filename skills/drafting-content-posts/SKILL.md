---
name: drafting-content-posts
description: >
  Draft LinkedIn posts for Pato Bichara's weekly content calendar. Handles three content types:
  quote posts (#FrasesBienCollective, lunes), session narrative posts (#JuevesCollective, jueves),
  and thematic free-topic posts (martes/miercoles). Use when Beto needs to draft a LinkedIn post,
  when the user says "draft a post", "write a LinkedIn post", "create content for [slot]",
  or provides a quote, transcript insight, or topic idea for development.
---

# Drafting Content Posts for Pato Bichara

Draft LinkedIn posts for Pato Bichara's weekly content calendar. Produces complete, ready-to-review drafts in Pato's authentic voice for any of the three weekly slot types.

## Before Drafting

1. Read the voice guidelines at [references/voice-guidelines.md](references/voice-guidelines.md)
2. Read the slot structure at [references/slot-structure.md](references/slot-structure.md)
3. For full strategy context, reference `/Users/patobichara/Code/pato-content-strategy/ESTRATEGIA-CONTENIDO.md`

## Workflow

### Step 1: Determine Post Type

Identify the post type from the user's input. Accept an explicit `type` parameter or infer:

- **`quote`** — User provides a phrase/quote from a Collective session → Monday slot, #FrasesBienCollective
- **`narrative`** — User provides an insight or analysis from a session transcript → Thursday slot, #JuevesCollective
- **`thematic`** — User provides a topic idea, opinion, or framework to develop → Tuesday/Wednesday slot, no branded hashtag

If the type is ambiguous, ask one clarifying question maximum, then proceed.

### Step 2: Identify the Pillar

Determine which content pillar this post belongs to:
- **Pilar 1 (45%):** Liderazgo y Estrategia en la Era de AI
- **Pilar 2 (30%):** Desarrollo de Talento y Cultura
- **Pilar 3 (25%):** Futuro del Trabajo

If not specified by the user, infer from the topic.

### Step 3: Draft the Post

Follow the structure template for the specific type (see references/slot-structure.md). Apply voice guidelines throughout.

#### For `type: quote`

**Required input:** The quote, session context, speaker (if not Pato)

Draft following this structure:
1. **Hook** — A curiosity-generating first line. Do NOT open with the quote itself; save it for the body. Techniques: challenge a common belief, present a surprising angle, open with a scene.
2. **Session context** — 2-3 sentences about the session and why this quote emerged. Be specific (name the topic, the audience type, the moment).
3. **The quote** — In its own paragraph, set apart. This is the centerpiece.
4. **Reflection** — What this means for leadership or business. 2-3 sentences connecting the quote to the reader's world.
5. **CTA** — An engagement question related to the quote's theme.
6. **Hashtags** — #FrasesBienCollective + 2-3 thematic hashtags

**Length:** 150-250 words. **Language:** Spanish.

#### For `type: narrative`

**Required input:** Central insight, narrative angle, supporting data/examples

Draft following this structure:
1. **Hook** — First line that challenges a belief or creates curiosity about the insight.
2. **Session context** — Brief (1-2 sentences). Enough to ground the reader, not a summary of the whole session.
3. **Insight development** — The core of the post. Develop the insight through: a framework, a contrast (what people think vs. what actually happens), a story with a turning point, or data + interpretation. This is where the value lives.
4. **Actionable takeaway** — What can the reader do with this? Be specific. Not "think about it" but "next time you [situation], try [action]."
5. **CTA** — Question or invitation to share their perspective.
6. **Hashtags** — #JuevesCollective + 2-3 thematic hashtags

**Length:** 200-350 words. **Language:** Spanish.

#### For `type: thematic`

**Required input:** Topic/idea, pillar (1/2/3). Optional: Pato's specific angle or notes, format preference.

**If format is text (default):**
1. **Hook** — Provide 3 options. Each must work as a standalone first line.
2. **Context** — Why this matters now. 1-3 sentences tied to current reality (industry trend, Collective observation, LatAm context).
3. **Framework/Argument** — 3-5 key points with evidence. Use: data points, personal experience (Bain, Harvard, Collective, Xochi Ventures), case studies, or frameworks.
4. **CTA** — Engagement question or soft Collective mention.
5. **Hashtags** — 3-5 thematic

**Length:** 200-400 words. **Language:** Spanish (English if user requests or topic warrants).

**If format is carousel:**
1. **Slide 1 (Hook):** Title (5-7 words, large) + subtitle (1 line of context)
2. **Slides 2-8:** One key point per slide. Each slide: short title + 2-3 bullets or a visual description.
3. **Slide final:** CTA + hashtags + "Sigue a Pato Bichara"
4. **Caption:** 2-3 lines of context + CTA for the LinkedIn caption accompanying the carousel.

### Step 4: Output the Draft

Present the draft in this format:

```
## Draft: [Descriptive Title]

**Type:** [quote | narrative | thematic]
**Slot:** [Lunes #FrasesBienCollective | Jueves #JuevesCollective | Martes/Miercoles tema libre]
**Pilar:** [1: Liderazgo/AI | 2: Talento/Cultura | 3: Futuro del Trabajo]
**Formato:** [Texto largo | Carrusel]
**Word count:** [X palabras]
**Idioma:** Espanol

---

[TEXTO COMPLETO DEL POST — listo para copiar y pegar en LinkedIn]

---

**Visual sugerido:** [Breve descripcion del visual recomendado: imagen de sesion, grafico de frase, data viz, foto de Pato, etc.]
**Notas para Beto:** [Flags, hooks alternativos, datos a verificar, o consideraciones]
```

## Guidelines

- **Especificidad sobre generalidad.** "En la ultima cohorte de Collective, 87% de los participantes..." es mejor que "La mayoria de las personas..."
- **Experiencia sobre opinion.** "Cuando estuve en Bain aprendimos a..." es mejor que "Los lideres deberian..."
- **Datos reales.** Si mencionas un dato de Collective (14,000 learners, 200 mentores), usalo con precision. Si no tienes el dato exacto, flaggealo en las notas para Beto.
- **Hook es todo.** Si la primera linea no detiene el scroll, el post falla. Invierte tiempo aqui.
- **LatAm siempre presente.** Narrar desde y para Latinoamerica. No importa el tema, el punto de vista es LatAm.
- **No pedir mas de 1 aclaracion.** Si falta info, draftea con lo que tienes y nota las assumptions en "Notas para Beto."
