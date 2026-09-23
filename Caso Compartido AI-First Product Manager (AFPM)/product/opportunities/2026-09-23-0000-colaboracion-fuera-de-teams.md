---
status: framed
segment: quienes conducen y quienes participan en reuniones de trabajo de 5 a 15 personas en Teams
personas: 01-carolina-duarte, 02-ruben-salgado
---

# Oportunidad: El trabajo conjunto de la reunión ocurre fuera de Teams

En las reuniones de trabajo de 5 a 15 personas, lo que se co-crea vive en herramientas externas: parte del equipo no participa en vivo y quien conduce paga después el costo de consolidarlo. Ahora, porque "el equipo ya usa otras herramientas" y "pagamos por funciones que no usamos" están entre los motivos de baja de plan.

## Segmento y personas

- **Sufren el problema:** Carolina (conduce: paga el cierre) y Rubén (participa: queda afuera del trabajo en vivo).
- **Sufre la consecuencia, no el problema:** Priya (IT) — renovación, shadow IT. Pesa en la viabilidad.
- **Excluido:** Martín (difusión masiva).
- **Persona faltante:** el participante fluido que prefiere la herramienta externa — la voz que refutaría el problema. Cubrir con `/generate-personas`.

## Señales

| Señal | Procedencia | Fuente |
|---|---|---|
| 29% de reuniones >5 personas comparte un link externo — incluye links de consulta (Jira, dashboards), sobreestima la co-creación | unverified | overview §4 |
| Whiteboard 5%, notas 8%, salas 9% de las reuniones | unverified | overview §4 |
| 19% de comentarios negativos post-reunión: colaboración durante la reunión (sin n) | unverified | overview §4 |
| Motivos de baja: "pagamos por funciones que no usamos", "el equipo ya usa otras herramientas" | unverified | overview §3–4 |
| 37% de las organizaciones tiene además Slack o Google Chat | unverified | overview §4 |
| Conductora pierde ~40 min por workshop consolidando; la mitad abre el link al día siguiente | synthetic | persona 01 |
| Participante no logra abrir el Miro compartido en el chat y no pide ayuda | synthetic | persona 02 |
| IT no puede explicar por qué se usa Miro en vez de lo licenciado; adopción de un dígito en capacidades avanzadas | synthetic | persona 03 |

## Resultado de negocio

Retención: reducir baja de plan / no renovación (3,6% en 12 meses, unverified), con foco en cuentas de más de 1.000 licencias (58% de las licencias).

## Restricciones

- La información debe quedar dentro del perímetro que audita IT (retención, grabación, acceso externo).
- Parte de los participantes entra desde móvil y tolera mal los cambios de interfaz.
- Lo nuevo se adopta vía pilotos de IT, que mueren si quien conduce no tiene tiempo de aprender en vivo.

## Creencias

Registradas en `product/overview.md` (sección "Creencias no verificadas"):

- [opportunity: colaboracion-fuera-de-teams] [value] En reuniones de trabajo de 5 a 15 personas que usan una herramienta externa, quien conduce dedica ≥20 min post-reunión a consolidar y distribuir lo producido, y al menos un tercio de los participantes no interactúa con el material durante la reunión.
- [opportunity: colaboracion-fuera-de-teams] [viability] Las cuentas que bajaron de plan o no renovaron tienen una proporción de reuniones con links a herramientas de co-creación ≥1,5 veces la de las cuentas que renovaron.

## Agenda de investigación

| Creencia | Instrumento | Decisión que habilita | Para cuándo |
|---|---|---|---|
| viability + tamaño | Datos propios: desagregar el 29% por tipo de link (co-creación vs. consulta) y comparar su proporción entre cuentas que renovaron y que bajaron | Si los links de co-creación son marginales o no difieren por churn → descartar o redimensionar antes de gastar en encuesta | 29/09/2026 |
| value | `/research-market`: ¿el mercado muestra que se paga por co-crear dentro de la reunión? (competidores, integraciones, alternativas) | Qué preguntas llegan a la encuesta | 29/09/2026 |
| value | `/design-survey` a quienes conducen: frecuencia, minutos de consolidación, participación; con opt-in | Si el costo supera el umbral (≥20 min, ≥1/3 sin interactuar) | 13/10/2026 |
| value | `/design-interview` con los opt-ins, priorizando respuestas que contradicen la creencia e incluyendo al participante fluido en la herramienta externa | Seguir a `/clarify-idea` o descartar | 20/10/2026 |

## Ideas candidatas (no evaluadas)

Ninguna surgió durante el encuadre.
