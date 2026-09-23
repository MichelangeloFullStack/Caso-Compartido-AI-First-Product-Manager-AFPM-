---
opportunity: colaboracion-fuera-de-teams
personas: 01-carolina-duarte, 02-ruben-salgado
channel: encuesta en producto (Teams, post-reunión)
expected_n: "<100 (direccional)"
created: 2026-09-22
---

# Encuesta: costo de consolidar y participación en reuniones con material externo

- **Objetivos de aprendizaje:**
  - **O1. Costo de consolidar.** ¿Quien conduce dedica ≥20 min después de la reunión a consolidar y distribuir lo producido en la herramienta externa? → Sostener o descartar la creencia [value] de la oportunidad.
  - **O2. Participación.** ¿Al menos un tercio de los participantes no interactúa con el material durante la reunión? ¿Es porque no pudo o porque no quiso? → Ídem. Además orienta la palanca: acceso (invitados, móvil) o dinámica de la reunión.
- **Encuestados:** quienes conducen reuniones de trabajo de 5 a 15 personas en Teams (persona Carolina). Se muestra dentro del producto al organizador, al cerrar una reunión de 5 a 15 participantes (filtro por telemetría).
- **Duración estimada:** 10 preguntas + 3 de reclutamiento, unos 4 minutos.
- **Límites conocidos:** n < 100 → reportar patrones, no porcentajes con precisión. O2 se mide según la percepción de quien conduce (proxy; es probable que sobreestime la participación). Hay autoselección de quienes responden encuestas post-reunión.

## Datos de telemetría a adjuntar a cada respuesta (no se preguntan)

- Tamaño de la cuenta (<100 / 100–1.000 / >1.000 licencias) y plan.
- Licencia Copilot en la cuenta; uso de Facilitator o notas Loop en las reuniones del encuestado → sirve para ver si los minutos de O1 bajan donde hay IA (riesgo señalado en `research/2026-09-23-0010-co-crear-en-la-reunion.md`).
- Renovó / bajó de plan en los últimos 12 meses (para cruzar después con la creencia [viability]; no se espera n suficiente).

## Screening

S1. En las últimas 4 semanas, ¿condujiste (no solo participaste) alguna reunión de Teams de 5 a 15 personas en la que el grupo trabajó en conjunto sobre un material en una herramienta fuera de Teams? Por ejemplo: escribir, agregar notas, votar u ordenar ideas en Miro, Mural, FigJam, Google Docs, Notion u otra. *Mostrar un dashboard, un ticket o una presentación no cuenta.* [opción única]
   - Sí
   - No
   - No estoy seguro/a
   → descalificar si responde "No" o "No estoy seguro/a"
   > Objetivo: perfil (O1, O2) — solo reuniones de co-creación, no de consulta (el 29% de links externos mezcla ambos).

S2. Pensá en la **más reciente** de esas reuniones. Las preguntas que siguen son sobre ella. ¿Cuántas personas participaron en total, contándote? [número]
   → descalificar si es menor a 5 o mayor a 15
   > Objetivo: perfil + denominador de O2.

## Preguntas

Q1. En las últimas 4 semanas, ¿cuántas reuniones como esa condujiste? [opción única]
   - 1
   - 2 a 3
   - 4 a 7
   - 8 o más
   > Objetivo: O1 — frecuencia; minutos × frecuencia = costo mensual.

Q2. Durante esa reunión, y sin contarte, ¿cuántas personas escribieron, agregaron, movieron o votaron algo en el material? [número, de 0 a (S2 − 1)]
   - [ ] No lo sé
   > Objetivo: O2 — Q2 ÷ (S2 − 1) = proporción que interactuó; umbral: ≤ 2/3.

Q3. Durante esa reunión, ¿alguna persona no pudo abrir o editar el material? [opción múltiple]
   - Sí, por un problema de acceso, cuenta o permisos
   - Sí, porque estaba conectada desde el celular
   - Sí, por otro motivo
   - No
   - No lo sé
   > Objetivo: O2 — separar "no pudo" de "no quiso".

Q4. Después de la reunión, ¿quién pasó a limpio, resumió o repartió lo que quedó en el material? [opción única]
   - Yo
   - Otra persona
   - Nadie
   - Todavía nadie, está pendiente
   > Objetivo: O1 — si el costo recae en quien conduce.

Q5. *(Solo si Q4 = "Yo")* En total, ¿cuánto tiempo te llevó? Sumá pasar a limpio, resumir, crear tareas y enviarlo. [opción única]
   - Menos de 10 minutos
   - 10 a 19 minutos
   - 20 a 39 minutos
   - 40 a 59 minutos
   - 1 hora o más
   - No lo recuerdo
   > Objetivo: O1 — minutos de consolidación; umbral: ≥20 (el corte coincide).

Q6. *(Solo si Q4 = "Yo")* ¿Qué incluyó ese trabajo? [opción múltiple]
   - Escribir un resumen o minuta
   - Crear o actualizar tareas (Jira, Planner u otra)
   - Copiar contenido del material a otro documento
   - Enviar el material o el resumen por chat o mail
   - Completar o reconstruir lo que quedó incompleto
   - Otra: ______
   > Objetivo: O1 — de qué se compone el costo.

Q7. ¿Qué es lo más difícil de cerrar y repartir lo que produce una reunión así? [abierta, opcional]
   > Objetivo: O1 — temas para codificar y para la guía de entrevista.

Q8. En esa reunión, ¿cómo participaron las personas que no tocaron el material? [abierta, opcional]
   > Objetivo: O2 — qué hacen los pasivos (hablan, miran, multitarea, no están).

## Screening + opt-in (reclutamiento para entrevistas)

R1. ¿Trabajás en Microsoft o en una empresa que desarrolla herramientas de reuniones o de colaboración? [Sí / No]
   → no es candidato/a si responde "Sí"
   > Filtro adicional al armar el pool: priorizar a quienes condujeron ≥2 reuniones así (Q1) y a quienes contradicen la creencia (<20 min o participación alta).

R2. ¿Aceptarías una conversación de 30 minutos sobre este tema? [Sí / No]

R3. *(Solo si R2 = "Sí")* ¿Cómo podemos contactarte? [abierta, opcional]
