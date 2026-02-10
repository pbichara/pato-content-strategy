# Workflow Definition: Weekly Content Production

## Scenario Metadata

**Workflow Name:** Weekly Content Production

**Description:** Proceso end-to-end de produccion de contenido semanal para las plataformas de Pato Bichara (LinkedIn e Instagram). Incluye captura de ideas, desarrollo de contenido por tipo de slot, consolidacion, revision, publicacion, engagement y tracking.

**Business Objective:**
- Posicionar a Pato como referente #1 en liderazgo y AI en LatAm
- Generar oportunidades de negocio para Collective Academy
- LinkedIn: 5 posts/semana (slots fijos con hashtags branded)
- Instagram: 2-3 posts/semana + Stories diarios (nuevo canal)
- Lograr >3% engagement LinkedIn, >5% Instagram

**Process Outcome:**
- Contenido semanal publicado en calendario, alineado a los 3 pilares estrategicos
- Engagement gestionado y metricas trackeadas

**Trigger:** Ciclo semanal continuo (multiples triggers por workflow)

**Type:** Augmented (actualmente Manual, en transicion a Augmented con AI)

**Current Owner(s):** Pato Bichara (CEO, aprobacion y engagement) + Beto (produccion y operacion)

---

## Estructura de Slots Semanales — LinkedIn

| Dia | Slot / Hashtag | Tipo de Contenido | Fuente |
|-----|---------------|-------------------|--------|
| Lunes | #FrasesBienCollective | Frase memorable de sesion Collective | Sesiones Collective |
| Martes | Tema libre | Post tematico (idea organica o investigacion) | Ideas Pato, tendencias, promocion |
| Miercoles | Tema libre | Post tematico (idea organica o investigacion) | Ideas Pato, tendencias, promocion |
| Jueves | #JuevesCollective | Insight/narrativa de sesion Collective | Transcript/presentacion de sesion |
| Viernes | #ViernesDeLibrosParaLideres | Recomendacion de libro | Backlog de libros + Readwise |

## Estructura de Slots Semanales — Instagram (NUEVO)

| Frecuencia | Tipo de Contenido | Fuente |
|-----------|-------------------|--------|
| 1-2/semana | Reels educativos (30-60 seg) | Repurposing de LinkedIn o contenido original |
| 1/semana | Carruseles visuales (5-8 slides) | Adaptacion de carruseles LinkedIn |
| Diario | Stories | Behind the scenes, encuestas, Q&A, libros |

---

## Workflows por Fase

### FASE 1: CAPTURA Y FUENTES DE IDEAS

#### FT-01: Captura de Ideas Organicas
**Owner:** Pato → Beto
**Trigger:** Conversacion con cliente/aprendedor, lectura de noticia/articulo, conversacion con lider, insight durante sesion
**Action:** Captura ad hoc de ideas de contenido que Pato genera. Las ideas fluyen a Beto por multiples canales.
**Output:** Idea registrada y capturada por Beto para desarrollo posterior
**Status actual:** Manual | In Production

**Sub-steps:**
1.1. Pato identifica una idea (conversacion, lectura, sesion, noticia)
1.2. Pato comunica la idea a Beto (Slack, WhatsApp, nota de voz, email)
1.3. Beto registra la idea en el backlog con contexto minimo (tema, fuente, pillar sugerido)

**Decision Points:**
- Es esta idea suficientemente fuerte para un post completo?
- A que pilar pertenece? (Liderazgo/AI 45%, Talento/Cultura 30%, Futuro del Trabajo 25%)
- Es timely (requiere publicacion inmediata) o evergreen?

**Failure Modes:**
- Ideas se pierden si no se capturan rapido
- Multiples canales de comunicacion dificultan el tracking
- Falta de contexto al registrar → idea pierde fuerza cuando se desarrolla despues

---

#### FT-02: Investigacion y Propuesta Proactiva
**Owner:** Beto
**Trigger:** Gap en calendario, solicitud de promocion de curso, tendencia relevante identificada
**Action:** Beto identifica oportunidades de contenido mediante monitoreo de tendencias LinkedIn, noticias relevantes, analisis de gaps en contenido reciente, o solicitudes internas. Usa el brief de voz de Pato como referencia.
**Output:** Tema propuesto a Pato para aprobacion
**Status actual:** Manual | In Production

**Sub-steps:**
2.1. Monitorear tendencias en LinkedIn (temas trending, posts de competidores/referentes)
2.2. Revisar noticias de industria (AI, educacion, liderazgo, LatAm)
2.3. Identificar gaps en contenido reciente (pilares sub-representados, formatos no usados)
2.4. Recibir solicitudes internas (promocion de programa Collective, milestone)
2.5. Proponer tema a Pato con angulo sugerido y slot recomendado

**Decision Points:**
- Es esta tendencia relevante para la audiencia de Pato (C-Suite, HR Leaders)?
- Hay un angulo diferenciado vs. lo que ya dicen otros?
- Encaja en un pilar estrategico?

**Failure Modes:**
- Propuestas genericas que no reflejan la voz de Pato
- Tendencias que ya pasaron cuando se publica el post
- No considerar el balance de pilares

---

### FASE 2: DESARROLLO DE CONTENIDO POR TIPO

#### FT-03: Extraccion de Frase Memorable
**Owner:** Beto
**Trigger:** Revision semanal de sesiones Collective
**Action:** Identificacion de frases memorables de sesiones Collective que generan reaccion visible en participantes (frases que "la gente fotografia"). Para slot #FrasesBienCollective (lunes).
**Output:** Frase seleccionada lista para desarrollo de post
**Status actual:** Manual | In Production

**Sub-steps:**
3.1. Revisar notas/transcripts de sesiones Collective de la semana
3.2. Identificar frases que generaron reaccion visible (aplausos, fotos, comentarios)
3.3. Seleccionar la frase mas fuerte de la semana
3.4. Documentar contexto de la frase (sesion, tema, speaker)

**Decision Points:**
- La frase funciona fuera de contexto o necesita explicacion?
- Es atribuible a Pato o a un mentor invitado?
- Es lo suficientemente impactante para LinkedIn?

**Failure Modes:**
- Semanas sin sesiones Collective → no hay fuente
- Frases que pierden impacto sin el contexto de la sesion

---

#### FT-04: Diseno de Post de Frase
**Owner:** Beto
**Trigger:** Frase memorable seleccionada (FT-03)
**Action:** Creacion de copy y contexto para la frase memorable seleccionada, mas seleccion/creacion de elemento visual y aplicacion de formato branded para #FrasesBienCollective.
**Output:** Draft completo en Google Doc con sugerencia visual para slot lunes
**Status actual:** Manual | In Production

**Sub-steps:**
4.1. Desarrollar copy: hook + contexto de la sesion + la frase + reflexion de cierre + CTA
4.2. Escribir en voz de Pato (educativo-practico, no predicar)
4.3. Seleccionar o crear elemento visual (imagen de la sesion, grafico con la frase, foto de Pato)
4.4. Aplicar formato branded (tipografia, colores Collective)
4.5. Agregar hashtags: #FrasesBienCollective + hashtags tematicos

**Data In:** Frase seleccionada, contexto de sesion, brief de voz de Pato
**Data Out:** Draft en Google Doc + visual sugerido

---

#### FT-05: Extraccion de Insight de Sesion
**Owner:** Beto
**Trigger:** Pato provee transcript o presentacion de sesion
**Action:** Analisis de transcript o presentacion de sesion Collective para identificar el insight o momento mas destacado que resonara con la audiencia LinkedIn. Para slot #JuevesCollective.
**Output:** Insight central y angulo narrativo identificado
**Status actual:** Manual | In Production

**Sub-steps:**
5.1. Recibir transcript o presentacion de sesion de Pato
5.2. Analizar el contenido completo buscando: momentos de tension/sorpresa, frameworks originales, datos impactantes, historias personales
5.3. Identificar el insight central (la "pepita de oro")
5.4. Definir angulo narrativo: como presentarlo para audiencia LinkedIn

**Decision Points:**
- Cual es el insight mas compartible?
- Funciona como standalone o necesita mucho contexto?
- Hay datos o frameworks que lo respalden?

---

#### FT-06: Desarrollo de Narrativa de Sesion
**Owner:** Beto
**Trigger:** Insight de sesion identificado (FT-05)
**Action:** Estructuracion del insight extraido en narrativa para audiencia LinkedIn, desarrollo de copy con voz de Pato, y creacion de elemento visual. Para slot #JuevesCollective (jueves).
**Output:** Draft completo en Google Doc para slot jueves
**Status actual:** Manual | In Production

**Sub-steps:**
6.1. Estructurar narrativa: Hook → Contexto de sesion → Insight/Framework → Takeaway → CTA
6.2. Desarrollar copy en voz de Pato
6.3. Incluir datos especificos o framework visual si aplica
6.4. Crear o seleccionar elemento visual
6.5. Agregar hashtags: #JuevesCollective + hashtags tematicos

---

#### FT-07: Seleccion de Libro desde Backlog
**Owner:** Beto
**Trigger:** Preparacion de contenido de viernes
**Action:** Seleccion del proximo libro a recomendar desde el backlog de libros leidos por Pato, priorizando libros recientes.
**Output:** Libro definido para la semana
**Status actual:** Manual | In Production

**Sub-steps:**
7.1. Revisar backlog de libros leidos por Pato
7.2. Priorizar libros recientes (2025-2026)
7.3. Verificar que no se haya recomendado recientemente
7.4. Confirmar disponibilidad de highlights/notas en Readwise

---

#### FT-08: Desarrollo de Recomendacion de Libro
**Owner:** Beto
**Trigger:** Libro seleccionado (FT-07)
**Action:** Creacion de recomendacion de libro con angulo de liderazgo, usando notas/highlights de Readwise, desarrollo de copy con voz de Pato, y creacion de elemento visual. Para #ViernesDeLibrosParaLideres.
**Output:** Draft completo en Google Doc para slot viernes
**Status actual:** Manual | In Production

**Sub-steps:**
8.1. Extraer highlights y notas de Readwise
8.2. Identificar el angulo de liderazgo (que leccion tiene este libro para un CEO?)
8.3. Desarrollar copy: Hook → Por que este libro → 3 ideas clave → Para quien es → CTA
8.4. Escribir en voz de Pato (personal, como si lo recomendara a un amigo CEO)
8.5. Crear visual (cover del libro, quote grafico)
8.6. Agregar hashtags: #ViernesDeLibrosParaLideres + hashtags tematicos

---

#### FT-09: Desarrollo de Post Tematico Libre
**Owner:** Beto
**Trigger:** Tema/idea aprobada por Pato (de FT-01 o FT-02)
**Action:** Desarrollo de posts para slots libres (martes/miercoles): investigacion complementaria, estructuracion de argumento/narrativa, desarrollo de copy con voz de Pato, decision de formato (texto corto vs carrusel), creacion de visuales.
**Output:** Draft completo en Google Doc para slot martes o miercoles
**Status actual:** Manual | In Production

**Sub-steps:**
9.1. Tomar idea aprobada del backlog
9.2. Investigar: datos de soporte, tendencias, articulos de referencia
9.3. Decidir formato: texto largo, carrusel, dato + reflexion
9.4. Estructurar: Hook → Contexto → Framework/Argumento → CTA
9.5. Desarrollar copy en voz de Pato
9.6. Crear visuales si aplica (carrusel, data viz)
9.7. Agregar hashtags tematicos

**Decision Points:**
- Es este tema texto o carrusel?
- Necesita investigacion adicional o alcanza con la idea original?
- En espanol o ingles?

---

### FASE 3: CONSOLIDACION Y APROBACION

#### FT-10: Consolidacion de Propuestas Semanales
**Owner:** Beto
**Trigger:** 5 drafts completados para la semana
**Action:** Organizacion de los 5 drafts completos (lunes a viernes) en Google Doc(s), verificacion de balance entre contenido branded vs tematico, y envio a Pato para revision.
**Output:** Propuesta semanal completa lista para revision de Pato
**Status actual:** Manual | In Production

**Sub-steps:**
10.1. Compilar los 5 drafts en orden de calendario
10.2. Verificar balance: contenido branded (lunes, jueves, viernes) vs. tematico libre (martes, miercoles)
10.3. Verificar distribucion de pilares contra targets (45/30/25)
10.4. Verificar que no haya redundancia tematica
10.5. Enviar a Pato via Google Doc compartido o Slack

---

#### FT-11: Revision y Aprobacion [NO-DELEGABLE]
**Owner:** Pato (exclusivo)
**Trigger:** Propuesta semanal enviada por Beto (FT-10)
**Action:** Revision de los 5 drafts por Pato con edicion minima enfocada en ajuste de palabras especificas para afinar tono/voz. Aprobacion via comentario en Google Doc o mensaje en Slack.
**Output:** Visto bueno para publicacion de la semana
**Status actual:** Manual | In Production

**Sub-steps:**
11.1. Leer cada draft completo
11.2. Editar palabras/frases especificas para afinar voz (edicion minima)
11.3. Verificar que historias personales sean precisas y apropiadas
11.4. Confirmar CTAs alineados con prioridades de negocio
11.5. Aprobar (comentario/emoji en Google Doc o mensaje en Slack)
11.6. Si requiere cambios mayores, enviar feedback especifico a Beto

**Decision Points:**
- Suena como yo o como influencer generico?
- Las historias/datos son correctos?
- Hay riesgo reputacional?
- El CTA empuja lo que necesito esta semana?

---

### FASE 4: PUBLICACION

#### FT-12: Publicacion en LinkedIn
**Owner:** Beto
**Trigger:** Aprobacion de Pato recibida (FT-11)
**Action:** Copia de copy final desde Google Doc, subida manual a LinkedIn, adicion de elementos visuales, aplicacion de hashtags branded, y publicacion directa en horario matutino.
**Output:** Post publicado en LinkedIn segun calendario (lunes a viernes)
**Status actual:** Manual | In Production

**Sub-steps:**
12.1. Copiar texto final del Google Doc aprobado
12.2. Crear nuevo post en LinkedIn
12.3. Pegar texto y verificar formato (saltos de linea, emojis si aplica)
12.4. Subir visual(es) adjunto(s)
12.5. Verificar hashtags
12.6. Publicar en horario matutino

---

#### FT-16: Adaptacion y Publicacion en Instagram [NUEVO]
**Owner:** Beto
**Trigger:** Post aprobado para LinkedIn (FT-11), o contenido original para Instagram
**Action:** Adaptar contenido de LinkedIn a formato Instagram (caption mas corta y conversacional), crear visuales especificos (Reels, carruseles), y publicar.
**Output:** 2-3 posts Instagram/semana + Stories diarios publicados
**Status:** Under Development

**Sub-steps:**
16.1. Seleccionar 2-3 posts de LinkedIn de la semana para repurposing
16.2. Adaptar caption: mas corta (50-70% del largo de LinkedIn), mas conversacional, hook en primera linea
16.3. Crear visuales Instagram-specific (formato cuadrado/vertical)
16.4. Para Reels: escribir script de 30-60 seg, grabar o crear con imagenes
16.5. Publicar en horarios optimos de Instagram
16.6. Preparar Stories diarios (BTS, polls, Q&A, reposts)

**Decision Points:**
- Que posts de LinkedIn se adaptan mejor a Instagram?
- Es Reel, carrusel, o post estatico?
- Necesita regrabacion o se adapta visualmente?

---

#### FT-17: Gestion de Stories de Instagram [NUEVO]
**Owner:** Pato + Beto
**Trigger:** Diario
**Action:** Publicacion de Stories diarios para mantener presencia y humanizar la marca. Mix de contenido preparado y espontaneo.
**Output:** 2-5 Stories publicados diariamente
**Status:** Under Development

**Sub-steps:**
17.1. Beto prepara templates de Stories para la semana (polls, Q&A, datos)
17.2. Pato graba/publica Stories espontaneos (BTS, viajes, eventos, lecturas)
17.3. Mezclar contenido preparado con espontaneo

**Calendario sugerido de Stories:**
- Lunes: BTS de Collective Academy
- Martes: Poll o Q&A sobre tema de la semana
- Miercoles: Compartir post de LinkedIn como Story
- Jueves: Quick tip o insight en video (30 seg)
- Viernes: Recomendacion de lectura del fin de semana
- Sabado/Domingo: Contenido personal/lighter

---

### FASE 5: ENGAGEMENT Y OPTIMIZACION

#### FT-13: Engagement y Respuestas [NO-DELEGABLE]
**Owner:** Pato (exclusivo)
**Trigger:** Post publicado (FT-12) y comentarios recibidos
**Action:** Gestion de engagement en posts publicados: monitoreo de reacciones, respuesta a comentarios, interaccion con audiencia. Ejecutado por Pato para mantener voz personal autentica.
**Output:** Interacciones gestionadas y audiencia engaged
**Status actual:** Manual | In Production

**Sub-steps:**
13.1. Monitorear comentarios en LinkedIn (prioridad: primeros 60 min post-publicacion)
13.2. Responder comentarios sustantivos (no solo "gracias")
13.3. Monitorear comentarios y DMs en Instagram [NUEVO]
13.4. Comentar proactivamente en 3-5 posts de otros lideres/semana (LinkedIn)
13.5. Flaggear conversaciones de alto valor (leads, partnerships, speaking invites)
13.6. Anotar preguntas frecuentes para futuro contenido

**Decision Points:**
- Que comentarios merecen respuesta detallada vs. simple?
- Hay feedback negativo que requiere manejo cuidadoso?
- Alguna conversacion debe moverse a DM?
- Hay oportunidad de negocio?

---

#### FT-14: Tracking de Metricas de Performance
**Owner:** Beto
**Trigger:** Posts publicados durante la semana
**Action:** Seguimiento de metricas de engagement, reach, comentarios y reacciones de los posts publicados. Realizado semanalmente.
**Output:** Reporte semanal de performance de contenido
**Status actual:** Manual | In Production

**Sub-steps:**
14.1. Exportar metricas de LinkedIn Analytics (engagement rate, impresiones, comentarios, shares)
14.2. Exportar metricas de Instagram Insights (reach, engagement, saves, shares) [NUEVO]
14.3. Registrar metricas en spreadsheet/dashboard
14.4. Identificar top 3 y worst performer
14.5. Calcular distribucion de pilares vs. targets
14.6. Registrar metricas de negocio (DMs comerciales, leads)
14.7. Preparar resumen para revision con Pato

---

#### FT-15: Analisis y Ajuste Estrategico
**Owner:** Pato + Beto
**Trigger:** Acumulacion de data de multiples semanas (mensual implicito)
**Action:** Revision periodica de performance de contenido, identificacion de patrones, ajuste de estrategia de temas y formatos basado en data.
**Output:** Ajustes estrategicos implementados en calendario de contenido
**Status actual:** Manual | In Production

**Sub-steps:**
15.1. Revisar tendencias mensuales (engagement por pilar, formato, dia)
15.2. Identificar patrones: que temas/formatos generan mas engagement?
15.3. Comparar contra targets (>3% LinkedIn, >5% Instagram)
15.4. Evaluar metricas de negocio (leads, partnerships, traffic a Collective)
15.5. Decidir ajustes: cambiar mix de pilares, probar formatos nuevos, ajustar horarios
15.6. Actualizar estrategia y backlog

---

## Flujo de Dependencias Completo

```
FUENTES DE IDEAS
[FT-01: Ideas Organicas] ──→ Backlog
[FT-02: Investigacion]  ──→ Backlog
                              ↓
DESARROLLO POR TIPO
[FT-03: Frase] → [FT-04: Post Frase]     → Draft Lunes
[Backlog]      → [FT-09: Post Libre]      → Draft Martes
[Backlog]      → [FT-09: Post Libre]      → Draft Miercoles
[FT-05: Insight] → [FT-06: Narrativa]     → Draft Jueves
[FT-07: Libro] → [FT-08: Recomendacion]   → Draft Viernes
                              ↓
CONSOLIDACION
[FT-10: Consolidacion Semanal] ← 5 drafts
                              ↓
APROBACION
[FT-11: Revision Pato] [NO-DELEGABLE]
                              ↓
PUBLICACION
[FT-12: LinkedIn] (diario, Beto)
[FT-16: Instagram] (2-3/semana, Beto) [NUEVO]
[FT-17: Stories] (diario, Pato + Beto) [NUEVO]
                              ↓
ENGAGEMENT
[FT-13: Engagement] [NO-DELEGABLE] (diario, Pato)
                              ↓
OPTIMIZACION
[FT-14: Tracking] (semanal, Beto)
[FT-15: Analisis] (mensual, Pato + Beto) → retroalimenta FT-01/02
```

---

## Context Shopping List

| # | Artifact | Status | Usado por |
|---|----------|--------|-----------|
| 1 | Estrategia de contenido (ESTRATEGIA-CONTENIDO.md) | EXISTS | FT-02, 09, 10, 15 |
| 2 | Brief de voz de Pato | EXISTS (implicito) | FT-04, 06, 08, 09 |
| 3 | Backlog de ideas | NEEDS CREATION (formalizar) | FT-01, 02, 09 |
| 4 | Transcripts/presentaciones de sesiones Collective | EXISTS (ad hoc) | FT-03, 05 |
| 5 | Backlog de libros + Readwise highlights | EXISTS | FT-07, 08 |
| 6 | Google Docs (drafts) | EXISTS | FT-04, 06, 08, 09, 10, 11, 12 |
| 7 | LinkedIn Analytics | EXISTS | FT-14, 15 |
| 8 | Instagram Insights | NEEDS SETUP | FT-14, 15 |
| 9 | Dashboard de metricas | NEEDS CREATION | FT-14, 15 |
| 10 | Templates visuales branded | NEEDS CREATION | FT-04, 06, 08, 16 |
| 11 | Datos Collective (14K learners, casos) | PARTIALLY EXISTS | FT-06, 09 |
| 12 | Lista de lideres para engagement | NEEDS CREATION | FT-13 |

---

## Notas

**Tiempo estimado semanal actual:**
- Beto: ~10-15 horas/semana (investigacion, drafting 5 posts, visuales, publicacion, tracking)
- Pato: ~3-4 horas/semana (ideas organicas, revision, engagement)
- Total: ~13-19 horas/semana

**Oportunidades de AI (mayor impacto):**
- FT-05/06 (Extraction de insights de sesion): AI puede analizar transcripts automaticamente
- FT-08 (Recomendacion de libro): AI puede extraer highlights de Readwise y estructurar draft
- FT-09 (Post tematico libre): AI puede acelerar investigacion y drafting
- FT-14 (Tracking): AI puede automatizar extraccion y analisis de metricas
- FT-16 (Instagram): AI puede repurposear LinkedIn a Instagram automaticamente
