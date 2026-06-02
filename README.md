# 👁️ InvestEye

### Mira tu startup con el ojo del inversionista.

InvestEye es un **coach guiado por IA** que toma a cualquier fundador y lo prepara para sentarse frente a un inversionista. No te interroga para tumbarte — te orienta y estructura, **una pregunta a la vez**, hasta que tu negocio resiste la mirada de quien firma el cheque. Al final te entrega un **Investor Readiness Dossier**: tu puntaje, tus fortalezas, tus huecos críticos y un plan de acción.

> Construido a partir de la charla **"Lo que los inversionistas ven… que tú no."** de **Guillermo Chapman** (Amador Holdings) en el **Founders Club · The Young Entrepreneurs Summit 2026** (Aurora Soho Mall, Panamá). Todo el crédito del marco conceptual es de la fuente; InvestEye solo lo vuelve una herramienta de práctica para que ningún founder se quede con el aprendizaje en una libreta.

---

## ¿Qué evalúa?

InvestEye recorre **20 checkpoints** en tres bloques, los mismos que un inversionista usa para decidir:

**🅰️ Preparando el pitch** — los 6 puntos que deben estar claros antes de un 1-on-1
Research del inversionista · Why now · TAM · Ama el problema · Equipo · Modelo de negocio

**🅱️ Lo que los inversionistas ven** — las 8 cosas igual o más importantes que la idea
Costo de capital · Obsesión con el problema · Talento como ventaja · Distribución gana · Tracción semana a semana · Ejecución no idea · Referencias & referrals · Misión vs flip

**🅲 Networking que sí funciona** — los 6 tips para construir relaciones con inversionistas
Investiga antes · Relaciones > red · Da primero · Deja que hable · Cierra con follow-up · No es competencia

---

## Cómo usarlo

### Opción 1 — Como skill de Claude Code / Claude (recomendado)
1. Copia la carpeta `investeye/` a tus skills:
   - **Claude Code:** `~/.claude/skills/investeye/`
   - **Codex:** `~/.agents/skills/investeye/`
2. Inicia una conversación y di: **"Quiero que me prepares para inversionistas con InvestEye"** (o simplemente *"grill me as an investor"*).
3. Responde una pregunta a la vez. Al final pide tu dossier.

### Opción 2 — En cualquier chat de IA (sin instalar nada)
¿No usas Claude Code? Funciona igual. Abre tu IA favorita y pega esto:

> *"Quiero que actúes como InvestEye: un coach que me prepara para inversionistas. Recorre estos 20 checkpoints uno por uno, dame tu recomendación en cada uno y al final un dossier de readiness."*

Luego pega el contenido de [`references/frameworks.md`](references/frameworks.md). Listo.

---

## ¿Por qué existe?

Porque el mejor aprendizaje de una conferencia es el que se aplica. Esta herramienta convierte 45 minutos de charla en una sesión de trabajo que cualquier fundador puede correr las veces que quiera, antes de cada reunión, antes de cada ronda.

**Es un regalo.** Úsalo, compártelo, mejóralo.

---

## Estructura

```
investeye/
├── SKILL.md                      # La skill: método, tono, workflow
├── README.md                     # Este archivo
├── LICENSE                       # MIT — libre para usar y compartir
└── references/
    ├── frameworks.md             # Los 20 checkpoints detallados
    └── dossier-template.md       # Plantilla del entregable final
```

## Licencia

MIT — libre para usar, compartir y adaptar. Si lo mejoras, manda un PR.
