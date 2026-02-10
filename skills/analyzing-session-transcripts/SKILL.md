---
name: analyzing-session-transcripts
description: >
  Analyze a Collective Academy session transcript or presentation to extract content for two
  weekly LinkedIn slots: memorable quotes for #FrasesBienCollective (Monday) and the central
  insight for #JuevesCollective (Thursday). Use when Beto has a transcript, presentation, or
  session notes and needs to extract content, when the user says "analyze this transcript",
  "extract quotes from this session", "find the insight", or provides session content for analysis.
---

# Analyzing Session Transcripts — Collective Academy

Analyze session transcripts or presentations from Collective Academy to extract content for two weekly LinkedIn slots simultaneously. One transcript feeds both Monday (quote) and Thursday (insight) posts.

## Before Analyzing

1. Read the voice guidelines at `../drafting-content-posts/references/voice-guidelines.md`
2. Read the slot structure at `../drafting-content-posts/references/slot-structure.md`
3. Review the extraction criteria at [references/extraction-criteria.md](references/extraction-criteria.md)

## Input

The user provides one of the following:
- Full session transcript (text or file)
- Presentation slides or notes
- Partial notes with key moments highlighted
- Audio transcript (auto-generated, may have errors)

If the input is an auto-generated transcript, flag potential transcription errors in the output.

## Workflow

### Step 1: Read and Understand the Session

Read the complete transcript/presentation. Identify:
- Session topic and theme
- Speaker(s) — Pato, guest mentor, panel
- Audience type (executives, mid-career, entrepreneurs, mixed)
- Overall arc of the session (problem → framework → application → reflection)

### Step 2: Extract Memorable Quotes (for FT-03 → Monday #FrasesBienCollective)

Scan for phrases that meet these criteria:
- **Standalone power:** The phrase works without any context — someone could read it cold and feel impact
- **Photographable:** This is the kind of thing a participant would take a photo of on screen
- **Specific, not generic:** "La velocidad mata menos empresas que la indecision" beats "Es importante tomar decisiones rapidas"
- **Attributable:** Clear who said it (Pato, guest, or participant)
- **Shareable:** Someone would repost this on their own LinkedIn

Extract the **top 3 quotes**, ranked by standalone power. For each, provide:
1. The exact quote (verbatim from transcript)
2. Speaker
3. Session context (what was being discussed when this emerged, 1-2 sentences)
4. Why it works (what makes it impactful, 1 sentence)
5. Suggested pillar (1: Liderazgo/AI, 2: Talento/Cultura, 3: Futuro del Trabajo)

### Step 3: Extract Central Insight (for FT-05 → Thursday #JuevesCollective)

Identify the single most powerful insight from the session — the "pepita de oro" that would resonate most with CEOs and HR Leaders on LinkedIn. This is NOT the main topic; it's the most surprising, useful, or perspective-shifting moment.

Look for:
- **Counterintuitive findings:** Something that challenges conventional wisdom
- **Original frameworks:** A mental model or decision framework presented for the first time
- **Turning-point stories:** A moment where the narrative shifted and the audience reacted
- **Data-driven surprises:** A statistic or data point that reframes how people think about the topic
- **Practical tools:** A specific technique or question that the audience can use immediately

Provide:
1. **Insight central:** The core idea in 1-2 sentences
2. **Angulo narrativo:** How to present this (story, framework, data + reflection, contrast, or debate)
3. **Datos de soporte:** Any statistics, examples, or case studies mentioned that reinforce the insight
4. **Por que resuena:** Why CEOs/HR Leaders would care (1 sentence)
5. **Hook sugerido:** 3 options for the LinkedIn first line
6. **Suggested pillar** (1/2/3)

### Step 4: Identify Bonus Content Opportunities

Note any additional content opportunities found in the transcript:
- Topics that could become thematic posts (FT-09, Tuesday/Wednesday)
- Data points or frameworks that could become carousels
- Quotes from participants that could inspire future content
- Questions from the audience that signal content gaps

List 2-3 bonus ideas with one sentence each.

### Step 5: Output

Present everything in this format:

```
## Session Analysis: [Session Topic/Title]

**Speaker(s):** [Names and roles]
**Audience:** [Type and approximate size if mentioned]
**Date:** [If mentioned]
**Overall theme:** [1 sentence summary]

---

### QUOTES — For Monday #FrasesBienCollective

**Quote 1 (Recommended):**
> "[Exact quote]"
- **Speaker:** [Name]
- **Context:** [1-2 sentences]
- **Why it works:** [1 sentence]
- **Pilar:** [1/2/3]

**Quote 2:**
> "[Exact quote]"
- **Speaker:** [Name]
- **Context:** [1-2 sentences]
- **Why it works:** [1 sentence]
- **Pilar:** [1/2/3]

**Quote 3:**
> "[Exact quote]"
- **Speaker:** [Name]
- **Context:** [1-2 sentences]
- **Why it works:** [1 sentence]
- **Pilar:** [1/2/3]

---

### INSIGHT — For Thursday #JuevesCollective

**Insight central:** [1-2 sentences]
**Angulo narrativo:** [story | framework | data + reflection | contrast | debate]
**Datos de soporte:** [Statistics, examples, case studies]
**Por que resuena:** [1 sentence on why C-Suite/HR Leaders care]
**Pilar:** [1/2/3]

**Hook options:**
1. [Hook option 1]
2. [Hook option 2]
3. [Hook option 3]

---

### BONUS — Additional Content Opportunities

1. [Idea + 1 sentence description]
2. [Idea + 1 sentence description]
3. [Idea + 1 sentence description]

---

**Notas para Beto:**
- [Any transcription errors flagged]
- [Quotes that need verification (speaker attribution unclear)]
- [Context that might need Pato's confirmation]
- [Suggested priority: which quote and which insight to develop first]
```

## Guidelines

- **Verbatim quotes only.** Do not paraphrase or "improve" the quotes. If the exact wording is unclear due to transcription quality, flag it.
- **One insight, not a summary.** The Thursday insight is NOT a recap of the session. It's the single most shareable, perspective-shifting moment.
- **Rank by LinkedIn shareability.** The best quote/insight is the one a CEO would repost, not necessarily the one that was most important in the session context.
- **Flag uncertainty.** If the transcript is unclear, if speaker attribution is ambiguous, or if a data point seems wrong, note it explicitly.
- **No drafting.** This skill extracts and organizes raw material. Use `drafting-content-posts` to turn the selected quote/insight into a full post.
