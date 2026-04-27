# SMMA — Especificaciones de Contenido DentBot

Este archivo le dice a Claude exactamente cómo trabajar contenido de redes sociales para DentBot sin que la tarea sea demasiado grande para un solo turno. Leerlo completo antes de generar cualquier pieza.

---

## Regla de oro: UNA PIEZA POR TURNO

Nunca generar más de una pieza de contenido completa por respuesta. Una pieza = un reel completo O un post completo. No los dos juntos. No varios a la vez.

Si el usuario pide "dame todos los reels de la semana", responder con el primero y preguntar si aprueba antes de continuar con el siguiente.

---

## Qué es una pieza completa

### Reel / TikTok
```
- Plataforma y duración estimada
- Ángulo neuromarketing
- Nota de producción (una línea: cómo grabarlo)
- HOOK: texto exacto para los primeros 3 segundos
- GUION COMPLETO: lo que se dice, con pausas marcadas como (Pausa.)
- CTA de interacción: pregunta o acción para comentarios
- Hashtags: 6-8 relevantes
```

### Post (Instagram / LinkedIn)
```
- Plataforma y ángulo
- Formato narrativo (storytelling / lista / insight / diagnóstico)
- CAPTION COMPLETO: listo para copiar y pegar, con saltos de línea correctos
- Hashtags: 6-8 relevantes
```

---

## Ángulos neuromarketing disponibles

Cada pieza usa exactamente uno de estos ángulos. El ángulo determina el disparador emocional que activa la atención.

| Ángulo | Disparador | Cuándo usarlo |
|--------|-----------|---------------|
| **Ahorro de Energía** | Agotamiento, repetición, tiempo robado | Dolores del día a día del odontólogo |
| **Supervivencia** | Pérdida económica, riesgo clínico, quedar atrás | Amenazas al negocio o al paciente |
| **Estatus** | Comparación social, percepción premium, posicionamiento | Diferenciación frente a competencia |
| **Autoridad** | Credibilidad clínica, confianza, dominio profesional | Contenido educativo o de posicionamiento experto |
| **Identidad** | Quién es el odontólogo moderno, pertenencia al grupo | Piezas que hablan del tipo de profesional que quiere ser |

---

## Voz y tono de marca

- Hablarle al odontólogo como Doctor/Doctora — respeto profesional, no condescendencia
- Nunca vender directamente en el cuerpo del contenido — la solución aparece naturalmente al final
- Tono: cálido, directo, colega que comparte algo útil — no vendedor, no corporativo
- El paciente siempre es el beneficiario final — cada feature se explica desde su impacto en el paciente
- Nunca usar la palabra "comprar" o "adquirir" en el contenido orgánico

**Frases de marca que pueden aparecer naturalmente:**
- *"Un paciente que se siente escuchado y un odontólogo que llega preparado."*
- *"Automatizar lo repetitivo libera lo humano."*
- *"No trabajar más. Trabajar diferente."*
- *"La relación no termina cuando termina la cita."*

---

## Estructura narrativa por formato

### Para Reels (fórmula que funciona)
1. **Hook** — Dolor específico o pregunta que para el scroll (primeros 3 segundos)
2. **Agitar** — Desarrollar el dolor con detalles concretos y reconocibles
3. **Pivot** — "Lo que sí funciona es..." o "Los consultorios que hacen X..."
4. **Solución suave** — DentBot aparece como la respuesta obvia, sin pitchear
5. **CTA** — Pregunta de engagement O "link en bio"

### Para Posts (fórmula que funciona)
1. **Primera línea gancho** — No pregunta, sí afirmación que genera tensión
2. **Historia o escenario** — Personaje concreto (Dr. X, La Dra. Y) en situación reconocible
3. **Separador** — Tres guiones `---` para respirar
4. **Diagnóstico** — Por qué pasó lo que pasó (sistema, no culpa personal)
5. **Separador**
6. **Solución** — Principio que funciona, DentBot como ejemplo natural
7. **Cierre** — Pregunta reflexiva O afirmación que invita a guardar/compartir

---

## Cómo pedirle una pieza a Claude

Usar este prompt exacto, adaptando los campos:

```
Escríbeme un [Reel / Post] para DentBot.
Concepto: [nombre del concepto — ej: "El papelito perdido"]
Ángulo: [uno de los 5 ángulos de la tabla]
Plataforma: [Instagram Reels / TikTok / LinkedIn / Instagram Feed]
Dolor que ataca: [una línea describiendo el problema del odontólogo]
```

Claude entrega una pieza completa. El usuario aprueba o pide ajuste. Luego se pide la siguiente.

---

## Registro de contenido — qué NO repetir

### Semana 1 (27 Abr – 3 May 2026) — `week1_4-27-26.md`
Dolores cubiertos: WhatsApp nocturno, guerra de precios por percepción, paciente que no volvió, fatiga por repetición de instrucciones, cancelaciones por ansiedad pre-consulta, fin de semana invadido, diferenciación high-ticket, saturación de recepción, erosión de autoridad por Google, fuga de ingresos de profilaxis.

### Semana 2 (4 – 10 May 2026) — `week2_5-4-26.md`
Dolores cubiertos: papelito de indicaciones perdido, fotocopia genérica vs. entregable premium, tiempo de consulta perdido en calmar miedos, reseñas orgánicas por experiencia WOW, PDF largo que nadie lee, infección por falta de comunicación post-op, odontólogo que hace 7 trabajos a la vez, boca a boca por momentos inesperados, tensión en sala de espera, competencia con franquicias mediante relación personal.

### Semana 3 (12 – 18 May 2026) — `week3_5-12-26.md`
**PENDIENTE** — Temas propuestos: implantes (seguimiento post-op), ortodoncia (abandono de tratamiento), estética (mantenimiento de carillas), reactivación de pacientes inactivos, saturación del asistente, identidad del odontólogo moderno, burnout en vacaciones, primera consulta de diagnóstico, manejo de objeciones de precio, flujo de caja y automatización.

---

## Formato de los archivos de semana

Cada archivo `weekN_fecha.md` sigue esta estructura:

```
# Contenido DentBot — Semana N (fechas)

## Calendario de publicación sugerido
[tabla con día / formato / pieza]

---

## REELS / TIKTOK
[5 reels completos]

---

## POSTS STORYTELLING B2B
[5 posts completos]

---

## Nota para la siguiente sesión
[qué se cubrió / qué explorar después]
```

---

## Stack de publicación

| Red | Formato principal | Frecuencia sugerida |
|-----|-----------------|-------------------|
| Instagram | Reels + Posts carrusel | 4-5 veces por semana |
| TikTok | Reels adaptados | 3-4 veces por semana |
| LinkedIn | Posts storytelling | 2-3 veces por semana |

Los reels de Instagram y TikTok usan el mismo guion — solo ajustar caption y hashtags por plataforma.

---

## Producto que se vende (contexto para cada pieza)

**DentBot** automatiza la anamnesis del paciente antes de que llegue al consultorio usando Tally + Make.com + Gemini AI + Notion. Genera dos fichas clínicas simultáneas: una para el odontólogo (PRE) y una para el paciente (POST).

**Precios:**
- Self-Setup: $9.99 USD — pago único — `https://pay.hotmart.com/U105362980Y`
- Setup Completo: $33 USD — pago único — `https://pay.hotmart.com/X105362860D` ⭐ más vendido
- Copilot: bono gratis en Setup Completo / order bump en Self-Setup

**CTA orgánico estándar:** "Link en bio" — nunca el link directo en el contenido orgánico.

**Mercado inicial:** Odontólogos independientes en Bogotá (Usaquén, Chapinero, Cedritos, Chía) con expansión a Colombia, México y Perú.
