# FT-01: Content Ideas Database — Implementation Summary

**Date:** 2026-02-11
**Status:** ✅ Completed
**Owner:** Beto (operational), Pato (ideas)

---

## What Was Done

Formalized the **Content Ideas Backlog** for FT-01 (Captura de Ideas Orgánicas) by adapting the existing "Content Production Tasks" database in Notion to match Pato's actual content production workflow.

### Database Location
**URL:** https://www.notion.so/2fd7fa62343c81d7bca8f284ad843b20
**Data Source ID:** `collection://2fd7fa62-343c-81d1-9a75-000be0548b93`

---

## Schema Changes

### 1. Updated Content Pillars
**Before:** Generic (Pillar 1-5)
**After:**
- Liderazgo y AI (45%) — blue
- Talento y Cultura (30%) — green
- Futuro del Trabajo (25%) — purple

### 2. Updated Content Types
**Before:** Video-centric (Short-Form Video, Long-Form Video, etc.)
**After:**
- Post LinkedIn — blue
- Carrusel LinkedIn — purple
- Book Recommendation — orange
- Reel Instagram — pink
- Carrusel Instagram — pink
- Story Instagram — gray

### 3. Added New Properties

| Property | Type | Options/Description |
|----------|------|---------------------|
| **Slot** | Select | Lunes #FrasesBienCollective, Martes libre, Miércoles libre, Jueves #JuevesCollective, Viernes #ViernesDeLibrosParaLideres, Instagram Flexible |
| **Source** | Select | Conversación con cliente, Sesión Collective (transcript), Lectura/Artículo, Noticia/Tendencia, Investigación Beto, Backlog de libros (Readwise) |
| **Urgency** | Select | Timely (publicar esta semana), Evergreen (flexible) |
| **Idea Origin** | Select | Pato (orgánica), Beto (investigación/propuesta) |

### 4. Updated Platform Options
**Before:** TikTok, Instagram, YouTube, LinkedIn, X, Blog
**After:** LinkedIn, Instagram only

---

## Status Workflow

The existing Status property already had a good workflow structure:

**Backlog:**
- Idea — captured but not scheduled

**In Progress:**
- Ideating — researching and planning
- Scripting — writing the draft
- Editing — draft complete, awaiting Pato's review
- Ready to Post — approved by Pato, scheduled

**Complete:**
- Published — live on platform(s)
- Archived — discarded or no longer relevant

---

## Documentation Created

### 1. Usage Guide
**URL:** https://www.notion.so/3047fa62343c8181a0d6e208f55f91f4
**Title:** "Guia de Uso: Content Ideas Database"

Covers:
- How to capture an idea (FT-01 process)
- Required vs optional fields
- Status workflow explanation
- Content pillars breakdown
- Weekly slots structure
- Failure modes and how to avoid them
- Tips for Beto and Pato

### 2. Example Entry
**URL:** https://www.notion.so/3047fa62343c81298c4ac9131af7664d
**Title:** "Ejemplo: Como las empresas LatAm estan usando AI para transformar RH"

Shows:
- Complete metadata (all fields filled)
- Original context from Pato
- Suggested angle
- Next steps for development

---

## How to Use (Quick Reference)

### For Beto: Capturing Ideas from Pato

When Pato sends an idea via Slack/WhatsApp/voice note/email:

1. **Create new entry** in database immediately (same day)
2. **Fill minimum required fields:**
   - Name: descriptive title
   - Idea Origin: "Pato (orgánica)"
   - Source: where it came from
   - Urgency: Timely vs Evergreen
   - Content Pillar: which of the 3 pillars
   - Priority: High/Medium/Low
   - Status: "Idea"

3. **Paste original message** in page body for context
4. **Add any notes** about angle, timing, or follow-up needed

### For Pato: Communicating Ideas

- Send ideas however is easiest (Slack, WhatsApp, voice note, conversation)
- No need to format perfectly — Beto will structure it
- **Helpful context to include:**
  - Where the idea came from ("conversación con X", "leí esto en Y")
  - If it's time-sensitive ("esto es para esta semana")
  - Suggested slot if you have one in mind ("esto para el viernes de libros")

---

## FT-01 Failure Modes — Now Resolved

| Failure Mode | How DB Solves It |
|--------------|------------------|
| **Ideas get lost if not captured quickly** | Single centralized DB, can capture in 2-3 min |
| **Multiple channels make tracking difficult** | All ideas consolidated in one place regardless of source |
| **Lack of context when registered → idea loses strength later** | Page body preserves original message + context |

---

## Integration with Other Workflows

This database feeds into:
- **FT-02** (Investigación y Propuesta Proactiva) — Beto adds his own research-based ideas with "Idea Origin: Beto"
- **FT-09** (Desarrollo de Post Temático Libre) — pulls from backlog for Martes/Miércoles slots
- **FT-10** (Consolidación) — checks pillar balance (45/30/25)
- **FT-15** (Análisis y Ajuste Estratégico) — reviews which idea sources perform best

---

## Views to Create (Recommended)

The database already has an "Ideas Backlog" view. Consider adding:

1. **This Week's Ideas** — Filter: Urgency = "Timely" AND Status = "Idea"
2. **By Pillar Balance** — Group by Content Pillar to verify 45/30/25 distribution
3. **Pato's Ideas** — Filter: Idea Origin = "Pato (orgánica)" to see organic ideas
4. **Ready for Development** — Filter: Status = "Idea" AND Priority = "High"

---

## Next Steps

- [ ] Beto: Start using this DB immediately for all new ideas
- [ ] Pato: Keep communicating ideas as usual — Beto will capture
- [ ] Team: Review backlog weekly to prioritize Timely ideas
- [ ] Team: Monthly review of pillar balance (45/30/25)

---

## Related Files

- Master workflow definition: `/outputs/weekly-content-production-definition.md`
- AI building blocks map: `/outputs/weekly-content-production-building-blocks.md`
- Content strategy: `/ESTRATEGIA-CONTENIDO.md`

---

## Notes

- This DB replaces informal idea tracking across Slack/WhatsApp/notes
- Ideas should be captured SAME DAY they're mentioned — don't rely on memory
- Weekly review of backlog ensures Timely ideas don't expire
- Monthly review ensures pillar balance stays on target (45/30/25)
