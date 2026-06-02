<div align="center">

# 👁️ InvestEye

### Mira tu startup con el ojo del inversionista.

*Un coach guiado por IA que te prepara para sentarte frente a quien firma el cheque.*

![License](https://img.shields.io/badge/license-MIT-black)
![Made for](https://img.shields.io/badge/para-fundadores-blue)
![Lang](https://img.shields.io/badge/idioma-español-orange)
![Type](https://img.shields.io/badge/Claude-skill-8A2BE2)

</div>

---

InvestEye toma a cualquier fundador y lo prepara para un pitch, un demo day o una ronda. No te interroga para tumbarte — te **orienta y estructura**, una pregunta a la vez, hasta que tu negocio resiste la mirada del inversionista. Al final te entrega un **Investor Readiness Dossier**: tu puntaje, tus fortalezas, tus huecos críticos y un plan de acción concreto.

> 🎤 Construido a partir de la charla **"Lo que los inversionistas ven… que tú no."** de **Guillermo Chapman** (Amador Holdings) en el **Founders Club · The Young Entrepreneurs Summit 2026** (Aurora Soho Mall, Panamá). Todo el crédito del marco conceptual es de la fuente; InvestEye solo lo vuelve una herramienta de práctica para que ningún founder se quede con el aprendizaje en una libreta.

---

## ⚡ Instálalo en 60 segundos

### La forma fácil — pídeselo a tu Claude
Abre Claude Code (o Claude Desktop con acceso a archivos) y pega esto:

> *"Instala la skill InvestEye desde https://github.com/VMlabshub/investeye clonándola en mi carpeta de skills, y luego prepárame para inversionistas con InvestEye."*

### La forma manual — un comando
**Claude Code:**
```bash
git clone https://github.com/VMlabshub/investeye.git ~/.claude/skills/investeye
```
**Codex / otros agentes:**
```bash
git clone https://github.com/VMlabshub/investeye.git ~/.agents/skills/investeye
```
Reinicia tu sesión y di: **"prepárame para inversionistas con InvestEye"** (o *"grill me as an investor"*).

### Sin instalar nada — en cualquier chat de IA
¿No usas Claude Code? Funciona igual. Pega esto en ChatGPT, Claude.ai, Gemini, el que uses:

> *"Quiero que actúes como InvestEye: un coach que me prepara para inversionistas. Recórreme estos checkpoints uno por uno, dame tu recomendación en cada uno y al final un dossier de readiness."*

…y a continuación pega el contenido de [`references/frameworks.md`](references/frameworks.md). Listo.

---

## 🔍 ¿Qué evalúa?

InvestEye recorre **20 puntos** en tres bloques — los mismos que un inversionista usa para decidir. Los 14 de los Bloques A y B se puntúan 🔴🟡🟢; los 6 de networking son coaching.

| 🅰️ Preparando el pitch | 🅱️ Lo que los inversionistas ven | 🅲 Networking que sí funciona |
|---|---|---|
| Research del inversionista | Costo de capital | Investiga antes |
| Why now | Obsesión con el problema | Relaciones > red |
| TAM | Talento como ventaja | Da primero |
| Ama el problema | Distribución gana | Deja que hable |
| Equipo | Tracción semana a semana | Cierra con follow-up |
| Modelo de negocio | Ejecución, no idea | No es competencia |
| | Referencias & referrals | |
| | Misión vs flip | |

**Principio central:** *Obsesión con el problema > enamoramiento con la solución. Ejecución > idea. Distribución gana.*

---

## 🧭 Cómo es una sesión

1. **Orienta** — te explica los tres lentes y arranca.
2. **Una pregunta a la vez** — pregunta, escucha, te da la versión fuerte de la respuesta, y puntúa.
3. **Steelman** — antes de darte un 🟢, argumenta el lado escéptico del inversionista. Solo pasas si tu respuesta sobrevive.
4. **Dossier final** — score sobre 14, fortalezas, huecos críticos y plan de acción semanal.
5. **Calibrado a tu etapa** — si eres pre-seed, no te castiga por no tener tracción todavía; te marca el siguiente hito.

---

## 📂 Qué hay dentro

```
investeye/
├── SKILL.md                      # La skill: método, tono, workflow
├── README.md                     # Este archivo
├── LICENSE                       # MIT
└── references/
    ├── frameworks.md             # Los 20 checkpoints detallados
    └── dossier-template.md       # Plantilla del entregable final
```

---

## 💛 Es un regalo

Hecho para la comunidad de fundadores del Founders Club. Úsalo antes de cada reunión, compártelo con otro founder, mejóralo. Si lo mejoras, manda un PR.

**Licencia:** [MIT](LICENSE) — libre para usar, compartir y adaptar.
