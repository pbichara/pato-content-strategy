---
name: drafting-book-recommendations
description: >
  Draft a LinkedIn book recommendation post for Pato Bichara's Friday slot #ViernesDeLibrosParaLideres.
  Takes a book title, author, and optionally Readwise highlights or personal notes, and produces a
  complete ready-to-review draft. Use when Beto needs to draft a book recommendation, when the user
  says "draft a book post", "write a book recommendation", "Viernes de libros", or provides a book
  title with highlights for the Friday slot.
---

# Drafting Book Recommendations — #ViernesDeLibrosParaLideres

Draft LinkedIn book recommendation posts for Pato Bichara's Friday slot. Produces a complete, ready-to-review draft that sounds like Pato recommending a book to a friend over coffee — not a Goodreads review.

## Before Drafting

1. Read the voice guidelines at `../drafting-content-posts/references/voice-guidelines.md`
2. Read the book post guidelines at [references/book-post-guidelines.md](references/book-post-guidelines.md)

## Input

The user provides:
- **Required:** Book title and author
- **Preferred:** Readwise highlights, personal notes, or key passages
- **Optional:** Pato's angle or why he read it, target pillar (1/2/3), specific audience

If only the title and author are provided, draft using general knowledge of the book and flag in notes that the draft needs enriching with real highlights.

## Workflow

### Step 1: Understand the Book and Angle

From the input, determine:
- Core topic and thesis of the book
- Which content pillar it maps to (1: Liderazgo/AI, 2: Talento/Cultura, 3: Futuro del Trabajo)
- The most relevant angle for Pato's audience (CEOs, founders, HR Leaders in LatAm)
- If Readwise highlights are provided, identify the 3-5 strongest passages

### Step 2: Select the 3 Key Ideas

Choose the 3 ideas from the book that are most **actionable** for Pato's audience. Prioritize:

1. Ideas that challenge something the audience currently believes or does
2. Frameworks or mental models they can apply this week
3. Data points that reframe how they think about the topic
4. Ideas with a clear LatAm connection or application

For each idea, if there's a strong Readwise highlight that supports it, use it as a direct quote from the book.

### Step 3: Draft the Post

Follow this structure:

1. **Hook** — First line that makes someone want to keep reading BEFORE they know which book it is. Never open with the book title. Techniques: pose the problem the book solves, share a surprising data point, connect to a personal experience.

2. **Why this book** — 2-3 sentences on what makes it special. Connect to Pato's experience (Collective, Bain, Harvard, Xochi) if natural. Why now? Why this one and not the other 50 books on the topic?

3. **3 key ideas** — The most applicable lessons for leaders. Each one:
   - Short title (5-7 words)
   - Why it matters (1-2 sentences)
   - Book quote if available from highlights

4. **Who it's for** — 1-2 sentences specifying the type of leader or situation that benefits most. Be specific: "Si estas escalando de 50 a 200 personas" > "Para todos los lideres."

5. **CTA** — Question that invites conversation about books or the topic.

6. **Hashtags** — #ViernesDeLibrosParaLideres + 2-3 thematic hashtags.

**Length:** 200-300 words.
**Language:** Spanish. Book quotes can stay in English with Spanish context.
**Tone:** Conversational-authentic (the most personal of all slots).

### Step 4: Generate Hook Options

Provide 3 hook options for the first line. Each must:
- Work as a standalone first line (stop the scroll)
- NOT mention the book title
- Create curiosity about the topic before revealing the book

### Step 5: Output

Present the draft in this format:

```
## Draft: Recomendacion de Libro — [Book Title]

**Type:** book-recommendation
**Slot:** Viernes #ViernesDeLibrosParaLideres
**Pilar:** [1: Liderazgo/AI | 2: Talento/Cultura | 3: Futuro del Trabajo]
**Libro:** [Titulo] — [Autor]
**Word count:** [X palabras]
**Idioma:** Espanol

---

### Hook Options

1. [Hook option 1]
2. [Hook option 2]
3. [Hook option 3]

---

### Post (using Hook 1)

[TEXTO COMPLETO DEL POST — listo para copiar y pegar en LinkedIn]

---

**Visual sugerido:** [Foto del libro, Pato leyendo, quote graphic con frase del libro, etc.]
**Notas para Beto:**
- [Si el draft se hizo sin highlights reales, flaggear]
- [Datos a verificar]
- [Hooks alternativos y por que se recomendo el #1]
- [Si hay highlights fuertes que no se usaron, listarlos como alternativas]
```

## Guidelines

- **No es una resena — es una recomendacion.** Diferencia clave: una resena evalua el libro objetivamente. Una recomendacion dice "esto me sirvio a mi, y creo que te puede servir a ti."
- **Hook es todo.** Si la primera linea dice "Hoy les recomiendo un libro", ya perdiste. El hook debe hacer que quieran leer antes de saber que libro es.
- **Seleccionar, no resumir.** 3 ideas bien elegidas > 10 ideas listadas. Elegir las mas accionables, no las mas "importantes."
- **Readwise highlights son oro.** Si hay buenos highlights, usarlos. Una cita directa del libro con buena seleccion es mas poderosa que una parafrasis.
- **Conectar con experiencia.** Los mejores posts de libros conectan la lectura con la vida real de Pato. "Esto me recordo a lo que vivimos en Collective cuando..." es mucho mejor que solo describir el libro.
- **No pedir aclaraciones.** Draftear con lo disponible. Si falta info, notar assumptions en "Notas para Beto."
