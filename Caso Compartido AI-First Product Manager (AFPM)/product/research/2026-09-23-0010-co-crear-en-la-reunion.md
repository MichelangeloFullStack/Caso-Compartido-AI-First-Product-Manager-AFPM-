---
source: secondary
method: web
date: 2026-09-23
question: ¿El mercado muestra que se paga por co-crear dentro de la reunión? (competidores, integraciones, alternativas)
opportunity: colaboracion-fuera-de-teams
---

# Research: co-crear dentro de la reunión

Fuentes consultadas el 2026-09-22 vía búsqueda web (4 carriles en paralelo). Cifras de terceros y de vendedores marcadas como tales.

**Tres hallazgos que cambian decisiones:**

1. **El mercado paga por consolidar, no por el lienzo.** La pizarra en vivo viene incluida o casi gratis en todas las suites (Webex Free, Zoom Basic, Loop en M365). Lo que se cobra aparte y tiene uso medido es la IA que convierte la reunión en notas y entregables: Copilot/Facilitator, Zoom AI Companion, "Take notes for me" de Google (110M asistentes/mes). Los whiteboards independientes están en retroceso: Google cerró Jamboard, Microsoft retira las apps sueltas de Whiteboard y Miro se vende a ~10% de su valoración de 2022. Esto refuerza la mitad "quien conduce consolida después" de la oportunidad, no la de "co-crear dentro".
2. **La fricción propia de Teams está en invitados, externos y móvil.** Miro, Mural y FigJam ya tienen *share to stage* en Teams, pero los invitados no pueden usar apps en la reunión, en móvil solo ven, y las notas Loop/Facilitator excluyen a externos. Es una palanca que solo Microsoft controla, y coincide con la persona Rubén.
3. **Reemplazar a Miro con algo nativo tiene evidencia y riesgo en contra.** Google admitió que sus clientes preferían a los especialistas. Además, los compromisos de Microsoft con la UE (sep-2025) exigen interoperabilidad con rivales durante 7–10 años. Integrar el artefacto externo y consolidar desde la reunión es más defendible que competir con él.

## Competidores directos: plataformas de reuniones

| Plataforma | Co-creación en vivo | Modelo de cobro | Señal de uso |
|---|---|---|---|
| Microsoft Teams | Whiteboard, notas colaborativas Loop, Facilitator (notas IA co-editables, agenda, timer) [verificado: support.microsoft.com/…/facilitator-in-microsoft-teams-meetings — 2026-09-22] | Loop incluido; Facilitator requiere 1 licencia Copilot en la reunión (Enterprise USD 30; Business USD 18 promo / 21) [verificado: microsoft.com/…/microsoft-365-copilot/pricing — 2026-09-22] | Sin datos públicos. Apps sueltas de Whiteboard se retiran el 16-oct-2026; fechas difieren entre fuentes [verificado: support.microsoft.com/…/retirement-standalone-microsoft-whiteboard-apps; mc.merill.net/message/MC1441775 — 2026-09-22] |
| Zoom Workplace | Whiteboard; Docs → Canvas (jun-2026); suite IA Canvas/Slides/Sheets "antes, durante y después" [verificado: news.zoom.com/zoom-launches-ai-productivity-suite — 2026-09-22] | 3 pizarras en Basic; ilimitado en Business. Precio del add-on inconsistente entre páginas oficiales (USD 2,07 vs 5,83) [verificado: zoom.us/pricing/whiteboard; zoom.com/…/online-whiteboard — 2026-09-22]. Suite IA: USD 10 add-on | AI Companion +184% MAU pagos; My Notes 1,5M MAU. Nada sobre Whiteboard/Docs [verificado: uctoday.com, may-2026 — 2026-09-22] |
| Google Meet | Sin pizarra propia: delega en FigJam, Lucidspark, Miro como add-ons [verificado: workspaceupdates.googleblog.com/2026/05 — 2026-09-22] | Gemini incluido en Business/Enterprise desde ene-2025 | "Take notes for me": 110M asistentes/mes, 8,5x interanual [verificado: 9to5google.com/2026/04/22 — 2026-09-22]. Jamboard cerrado dic-2024 porque los clientes preferían terceros [verificado: workspaceupdates.googleblog.com/2023/09 — 2026-09-22] |
| Webex | Whiteboard co-editable; Slido para votar y preguntar [verificado: help.webex.com/article/vwot6eb — 2026-09-22] | Whiteboard ilimitado incluso en Free [verificado: pricing.webex.com — 2026-09-22] | Desconocido |
| Slack | Huddles + notas IA en canvas; sin externos [verificado: slack.com/help/articles/31377193680019 — 2026-09-22] | Planes pagos | Desconocido |

**Qué prueba:** hay demanda de co-crear sin salir de la llamada; todos lo construyeron o lo integraron. **Qué no prueba:** que el segmento abandone Miro/Docs por lo nativo, ni disposición a pagar por el lienzo (viene incluido).

## Alternativas: herramientas externas e integraciones

| Herramienta | Dentro de Teams | Escala | Facilitación |
|---|---|---|---|
| Miro | Share to stage; invitados no pueden usar apps, en móvil solo ven [verificado: help.miro.com/…/4411292563602 — 2026-09-22] | ~100M usuarios, ~4M pagos, ~USD 600M ARR; compra por Bending Spoons USD 1.355M (10-sep-2026) [verificado: investors.bendingspoons.com; techcrunch.com/2026/09/10 — 2026-09-22] | Miro Engage (retros, workshops) en plan Business |
| Mural | Lienzo en la reunión con votación [verificado: mural.co/partners/microsoft/teams — 2026-09-22] | Sin cifras actuales; >75% Fortune 100 en 2021 | Workshops "kickoff to retro" |
| FigJam | Share to stage; "open session" para sin cuenta [verificado: help.figma.com/…/7405452518423 — 2026-09-22] | Sin cifras propias | Timer, votación, resúmenes IA; se vende como "online meeting tool" |
| Lucidspark | Teams: desconocido; Zoom y Meet sí | 100M+ usuarios (Lucid) | Timer, votación, breakout boards |
| Notion | Sin app en reunión; AI Meeting Notes post-reunión [verificado: notion.com/help/ai-meeting-notes — 2026-09-22] | Desconocido | — |

**Fricción documentada en Teams:** invitados no pueden agregar apps; anónimos solo si la política lo permite [verificado: learn.microsoft.com/microsoftteams/apps-external-users, may-2026 — 2026-09-22]. Externos bloqueados en Whiteboard, caso sin resolver (Q&A 2023). En un taller con link público de Miro, ~20% no pudo entrar por pedido de cuenta (comunidad Miro, 2021) — señal, no hecho.

**No-consumo:** no hay datos públicos de cuántas reuniones se resuelven solo compartiendo pantalla o con notas sueltas. Desconocido. Única cifra: 23% dice que a las reuniones virtuales les falta un espacio visual compartido (Lucid, 2020, encuesta del propio vendedor).

## Precios y modelos de negocio

| Producto | Modelo | Gratis | Pago (USD/usuario/mes, anual) | Externos |
|---|---|---|---|---|
| Miro | Freemium separado | 3 tableros | Starter 8 · Business 20 · Enterprise a medida | Guests y visitors gratis [verificado: miro.com/pricing — 2026-09-22] |
| Mural | Freemium separado | 3 murales | Team+ 9,99 · Business 17,99 | Visitors gratis [verificado: mural.co/pricing — 2026-09-22] |
| FigJam | Asiento "Collab" de Figma | 3 archivos | 3–5 [fuente de terceros, sin confirmar] | Desconocido |
| Lucidspark | Separado | 3 tableros, sin facilitación | 9–10 [fuente de terceros, sin confirmar] | Desde Team |
| Suites (Teams, Webex, Zoom Business) | Incluido | — | Sin costo adicional | — |
| M365 Copilot | Add-on IA | Copilot Chat limitado | 18–30 | Externos no ven Facilitator |

- **Se cobra al organizador, no a los asistentes**: invitados y visitantes gratis en todas las herramientas externas.
- **La entrada es viral (freemium), pero el dinero lo pone IT**: ~90% de los ingresos de Miro viene de business/enterprise [verificado: techcrunch.com/2026/09/10 — 2026-09-22]. Empresas que ya tienen Whiteboard/Loop incluido pagan Miro igual: indica una brecha de capacidad o hábito, no de precio (inferencia).
- **Valor del whiteboard suelto en caída**: Miro se vende a ~2,3x ARR; TechCrunch lo atribuye a que "businesses started preferring suites".

## Tendencias y posicionamiento

- **Mercado**: whiteboard colaborativo ~USD 3.800M, crecimiento de dos dígitos (informes de pago, calidad baja; solo dirección) [verificado: mordorintelligence.com; precedenceresearch.com — 2026-09-22]. Gartner (oct-2025, vía resumen de Lucid): mercado maduro que se consolida en suites.
- **Best-of-breed bajo presión**: despidos en Miro (7% en 2023, 18% en 2024) y Mural (2022–2024); Miro se reposiciona como "innovation workspace" con agentes IA, sin foco en reuniones [verificado: miro.com/canvas — 2026-09-22].
- **Tool sprawl en alza**: 305 apps promedio por organización en 2025 (275 en 2024); 9,5 apps redundantes en "team collaboration" (Zylo, vendedor) [verificado: zylo.com/blog/saas-consolidation — 2026-09-22].
- **Regulación UE**: compromisos aceptados el 12-sep-2025 (interoperabilidad, suites sin Teams, portabilidad; 7–10 años, aplicados globalmente) [verificado: slaughterandmay.com — 2026-09-22].
- **Posicionamiento**: el "antes" (agenda) y el "después" (resúmenes, tareas) están llenos. Está relativamente vacío el "durante" estructurado: artefactos co-creados en vivo que la IA consolida en la reunión (votos, clusters, decisiones) y que suman a los pasivos. Zoom (AI canvases) y Facilitator apenas empiezan ahí.
- **Participación en reuniones**: la probabilidad de multitarea con email sube 1,70x con 6–10 asistentes y 2,16x con más de 10, frente a reuniones de 2 (telemetría Microsoft 2020, CHI 2021) [verificado: hci.stanford.edu/…/CHI2021-RemoteMeetingMultitask.pdf — 2026-09-22]. Los asistentes en mute toda la reunión pasaron de 4,8% a 7,2% entre 2022 y 2023 (Vyopta, vendedor) [verificado: axios.com/2024/06/24 — 2026-09-22].
- **Tiempo de consolidación post-reunión: desconocido.** Ningún estudio creíble lo mide.

## Impacto en creencias

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| [opportunity: colaboracion-fuera-de-teams] [value] Quien conduce dedica ≥20 min post-reunión a consolidar y ≥1/3 de participantes no interactúa con el material | **Apoya la dirección, no dice nada del umbral** | El mercado monetiza masivamente la consolidación post-reunión (Copilot, AI Companion, Take notes for me: 110M/mes), lo que indica que el dolor existe. La pasividad crece con el tamaño de la reunión (CHI 2021; Vyopta). Pero nadie mide minutos de consolidación, y ninguna fuente aísla reuniones con herramienta externa. Riesgo a vigilar: donde hay Copilot/Facilitator, los 20 min podrían estar bajando. |
| [opportunity: colaboracion-fuera-de-teams] [viability] Las cuentas que bajaron o no renovaron tienen ≥1,5x reuniones con links a co-creación | **No dice nada** | Requiere datos internos. Contexto mixto: "las empresas prefieren suites" (TechCrunch sobre Miro) sugiere que las externas pierden frente a la suite; el tool sprawl en alza (Zylo) sugiere lo contrario. Ninguna fuente vincula herramientas externas con churn de una suite. |

## Qué sigue necesitando research primario

- **Datos propios (ya en la agenda, 29/09)**: desagregar el 29% de links por tipo y por churn. Sumar: uso real de Whiteboard, Loop y Facilitator en reuniones de 5–15, y qué proporción de esas reuniones tiene invitados o externos.
- **Encuesta a quienes conducen (cuánto, con qué frecuencia)**: minutos de consolidación; tipo de reunión (workshop vs. recurrente); si hay externos o invitados; si usan Copilot/Facilitator u otro recap con IA; cuántos participantes no abren el material.
- **Entrevistas (por qué, qué hacen hoy)**: por qué eligen Miro/Docs habiendo Whiteboard/Loop (capacidad, hábito, externos); qué parte de la consolidación ya resuelve la IA y cuál no; la voz del participante fluido en la herramienta externa.
