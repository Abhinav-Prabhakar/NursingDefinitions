<div align="center">
  <img src="assets/og.png" alt="one·liners — Nursing, in one line." width="100%" />
</div>

<div align="center">

# one·liners · Nursing & NCLEX

**Nursing, in one line.**

A calm NCLEX companion: 347 definitions across 6 subjects — fundamentals, health assessment, safety and infection control, medical-surgical, maternal-child and mental health — with an adaptive two-way quiz and a memory of what you actually know.

<a href="https://abhinav-prabhakar.github.io/NursingDefinitions/">
  <img src="https://img.shields.io/badge/OPEN%20THE%20APP-live-4a7fc1?style=for-the-badge&logo=githubpages&logoColor=white" alt="Open the live app" />
</a>

<br /><br />

<img src="https://img.shields.io/badge/definitions-347-4a7fc1?style=flat-square" alt="347 definitions" />
<img src="https://img.shields.io/badge/subjects-6-100e14?style=flat-square" alt="6 subjects" />
<img src="https://img.shields.io/badge/PWA-offline--ready-100e14?style=flat-square&logo=pwa&logoColor=white" alt="PWA offline ready" />
<img src="https://img.shields.io/badge/backend-none-d0577a?style=flat-square" alt="No backend" />
<img src="https://img.shields.io/badge/vanilla-HTML%20%C2%B7%20CSS%20%C2%B7%20JS-2f9e7e?style=flat-square" alt="Vanilla HTML CSS JS" />
<img src="https://img.shields.io/badge/deploy-GitHub%20Pages-100e14?style=flat-square&logo=github&logoColor=white" alt="GitHub Pages" />

</div>

<p align="center"><sub>Screenshots use sample study data. The app itself starts clean, on your device.</sub></p>

---

## Why this exists

The NCLEX tests judgment, but judgment is built on vocabulary you can produce under pressure: *Hegar sign*, *healthcare-associated infection*, *dysrhythmia*, *therapeutic communication*. **one·liners** gives each term one line, quizzes it both ways, and brings the shaky ones back until they stick.

Warm paper, soft rounded type, scrub colours, and a bedside monitor that keeps a steady rhythm. No accounts, no server, no noise — practise on a break, on your phone, offline.

> **Recognition is not recall.** Picking *Hegar sign* from a list is not the same as naming it from the finding. So the quiz asks both ways.

---

## Screenshots

<table>
  <tr>
    <td width="50%">
      <img src="assets/screenshot-home-light.png" alt="Home in light mode" width="100%" />
      <p align="center"><sub><strong>Light by default</strong> · today, activity, subject mastery</sub></p>
    </td>
    <td width="50%">
      <img src="assets/screenshot-home-dark.png" alt="Home in dark mode" width="100%" />
      <p align="center"><sub><strong>Dark when you choose it</strong> · remembered across visits</sub></p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="58%">
      <img src="assets/screenshot-subject-light.png" alt="A subject's definitions with per-definition mastery" width="100%" />
      <p align="center"><sub><strong>Every definition has a memory.</strong> Hover a row for its mastery and source.</sub></p>
    </td>
    <td width="42%">
      <img src="assets/screenshot-quiz-dark.png" alt="A two-way quiz in dark mode" width="100%" />
      <p align="center"><sub><strong>Answers explain themselves.</strong> The definition, and what you picked.</sub></p>
    </td>
  </tr>
</table>

<div align="center">
  <img src="assets/screenshot-mobile-subject.png" alt="one·liners on a phone" width="310" />
  <p><sub><strong>320 → 1440px.</strong> The same quiet interface, not a crushed desktop.</sub></p>
</div>

---

## What's inside

**347 one-liners** across **6 subjects**, written for nclex-rn candidates.

- **Core** — Fundamentals of Nursing, Health Assessment, Safety and Infection Control
- **Clinical** — Medical-Surgical Nursing, Maternal and Child Health, Mental Health Nursing

| Subject | Definitions | Units |
| --- | ---: | --- |
| **Fundamentals of Nursing** | 60 | Nursing process · Vital signs · Hygiene and comfort · Mobility and safety · Nutrition and elimination · Documentation and communication |
| **Health Assessment** | 56 | Health history · Physical exam techniques · Head and neck · Thorax and lungs · Abdomen · Extremities and skin |
| **Safety and Infection Control** | 56 | Infection control principles · Hand hygiene and PPE · Isolation precautions · Medication safety · Fall and restraint safety · Emergency preparedness |
| **Medical-Surgical Nursing** | 60 | Cardiovascular · Respiratory · Endocrine · Gastrointestinal and renal · Neurological and musculoskeletal · Fluids and electrolytes |
| **Maternal and Child Health** | 59 | Antepartum · Intrapartum · Postpartum · Newborn · Pediatric growth and development · Pediatric illness |
| **Mental Health Nursing** | 56 | Therapeutic communication · Mood disorders · Psychotic disorders · Anxiety and trauma · Substance use · Crisis and suicide |

Every definition is one sentence, 8–28 words, and carries a source locator. Hover a
definition's mastery rail to see where it came from. Coverage, gaps and assumptions are
documented in [`data/README.md`](data/README.md).

---

## Two directions of recall

Every round mixes both question types, balanced 5/5. You cannot coast on recognition.

| Prompt | You choose | What it trains |
| --- | --- | --- |
| `Dysrhythmia` | one of four definitions | term → meaning |
| “Softening of the lower uterine segment in early pregnancy.” | one of four terms | meaning → term |

- **The term is never in the question.** When a definition has to mention its own term, the
  quiz blanks it out, so meaning → term tests meaning.
- **Wrong answers that look right.** Distractors come from each definition's curated
  look-alikes, then from similar wording in the same unit — never four random strangers.
- **Adaptive sampling.** The three weakest definitions are guaranteed a slot; the rest are
  weighted toward low mastery.
- **Keyboard complete.** <kbd>1</kbd>–<kbd>4</kbd> or <kbd>A</kbd>–<kbd>D</kbd> to choose,
  <kbd>Enter</kbd> for next, <kbd>Esc</kbd> to leave, <kbd>r</kbd> to repeat a round.

---

## A memory you can see

Mastery is one confidence score per definition, stored locally: **+30%** for a correct answer,
**−40%** for a miss. Four clean answers reach 100%.

| After | Score | Reads as |
| --- | --- | --- |
| no attempts | 0% | `new` |
| 1 correct | 30% | `learning` |
| 2 correct | 60% | `familiar` |
| 3 correct | 90% | `solid` |
| a miss | −40% | re-learn |

The subject page shows a 2px bar on every definition; cards show a bar profile of the whole
subject; the home page has a daily goal stack and a quiet, monochrome activity trail.

---

## Offline, installable, private

- **Full PWA** — manifest, service worker, maskable icons. Works offline after the first load.
  Install from the browser's own menu (Chrome: the install icon in the address bar; iOS Safari:
  **Share → Add to Home Screen**; macOS Safari: **File → Add to Dock**).
- **No accounts, no analytics, no server.** Progress lives in `localStorage` under
  `oneliners.nursing-and-nclex.*` and never leaves the device.
- **Self-hosted type** — Inter, Nunito. No external font requests.
- **Light by default**, dark when you choose it, remembered before first paint.

---

## Sources

| Source | Publisher | License |
| --- | --- | --- |
| [Standard Precautions for All Patient Care](https://www.cdc.gov/infection-control/hcp/standard-precautions/) | Centers for Disease Control and Prevention (CDC) | Public domain (US government) |
| [Nursing Fundamentals 2e](https://wtcs.pressbooks.pub/nursingfundamentals/) | WisTech Open (Open RN) | CC BY 4.0 |
| [Nursing Fundamentals 2e](https://wtcs.pressbooks.pub/nursingfundamentals/) | WisTech Open (Open RN) | CC BY 4.0 |
| [Nursing Skills 2e](https://wtcs.pressbooks.pub/nursingskills/) | WisTech Open (Open RN) | CC BY 4.0 |
| [Fundamentals of Nursing](https://openstax.org/books/fundamentals-nursing) | OpenStax (Rice University) | CC BY-NC-SA 4.0 |
| [Maternal Newborn Nursing](https://openstax.org/books/maternal-newborn-nursing) | OpenStax (Rice University) | CC BY-NC-SA 4.0 |
| [Medical-Surgical Nursing](https://openstax.org/books/medical-surgical-nursing) | OpenStax (Rice University) | CC BY-NC-SA 4.0 |
| [Population Health for Nurses](https://openstax.org/books/population-health) | OpenStax (Rice University) | CC BY-NC-SA 4.0 |
| [Psychiatric-Mental Health Nursing](https://openstax.org/books/psychiatric-mental-health) | OpenStax (Rice University) | CC BY-NC-SA 4.0 |

Definitions are paraphrased one-liners, not excerpts. Raw source material is not redistributed.

> [!IMPORTANT]
> Educational vocabulary only; not medical advice, clinical training, or licensure guidance.

---

## Run it locally

```bash
# A server is required: the app fetches its data.
python3 -m http.server 8000
# → http://localhost:8000/
```

No build step, no dependencies. `index.html` is the whole app.

```text
.
├── index.html             # the entire app
├── manifest.webmanifest   # PWA manifest
├── sw.js                  # offline app shell + data cache
├── data/
│   ├── curriculum.json    # sections and subjects the app loads
│   ├── sources.json       # where every definition comes from
│   ├── collection.json    # scope, audience, assumptions
│   ├── README.md          # coverage report
│   └── subjects/*.json    # one file per subject
└── assets/                # icons, social card, screenshots, fonts
```

---

## The one·liners family

Same instrument, different vocabularies. Each has its own look, data and progress.

| Collection | Repository |
| --- | --- |
| [Electronics, in one line.](https://abhinav-prabhakar.github.io/ECEDefinitions/) | [`Abhinav-Prabhakar/ECEDefinitions`](https://github.com/Abhinav-Prabhakar/ECEDefinitions) |
| [Anatomy and physiology, in one line.](https://abhinav-prabhakar.github.io/AnatomyDefinitions/) | [`Abhinav-Prabhakar/AnatomyDefinitions`](https://github.com/Abhinav-Prabhakar/AnatomyDefinitions) |
| [Electricity, in one line.](https://abhinav-prabhakar.github.io/ElectricalCodeDefinitions/) | [`Abhinav-Prabhakar/ElectricalCodeDefinitions`](https://github.com/Abhinav-Prabhakar/ElectricalCodeDefinitions) |
| [HVAC, in one line.](https://abhinav-prabhakar.github.io/HVACDefinitions/) | [`Abhinav-Prabhakar/HVACDefinitions`](https://github.com/Abhinav-Prabhakar/HVACDefinitions) |
| [Medicine, in one line.](https://abhinav-prabhakar.github.io/MedicalTerminologyDefinitions/) | [`Abhinav-Prabhakar/MedicalTerminologyDefinitions`](https://github.com/Abhinav-Prabhakar/MedicalTerminologyDefinitions) |
| **[Nursing, in one line.](https://abhinav-prabhakar.github.io/NursingDefinitions/)** | [`Abhinav-Prabhakar/NursingDefinitions`](https://github.com/Abhinav-Prabhakar/NursingDefinitions) |
| [Pharmacology, in one line.](https://abhinav-prabhakar.github.io/PharmacologyDefinitions/) | [`Abhinav-Prabhakar/PharmacologyDefinitions`](https://github.com/Abhinav-Prabhakar/PharmacologyDefinitions) |
| [Plumbing, in one line.](https://abhinav-prabhakar.github.io/PlumbingDefinitions/) | [`Abhinav-Prabhakar/PlumbingDefinitions`](https://github.com/Abhinav-Prabhakar/PlumbingDefinitions) |
| [Software, in one line.](https://abhinav-prabhakar.github.io/SoftwareInterviewDefinitions/) | [`Abhinav-Prabhakar/SoftwareInterviewDefinitions`](https://github.com/Abhinav-Prabhakar/SoftwareInterviewDefinitions) |
| [The law, in one line.](https://abhinav-prabhakar.github.io/LegalDefinitions/) | [`Abhinav-Prabhakar/LegalDefinitions`](https://github.com/Abhinav-Prabhakar/LegalDefinitions) |

### Credits

Definitions are paraphrased from the openly licensed nursing texts listed above. Built on the [one·liners](https://github.com/Abhinav-Prabhakar/ECEDefinitions) engine. Fonts: Inter, Nunito (SIL Open Font License 1.1).

<div align="center">
  <sub>If this helps you pass the NCLEX, star the repo — and go get some sleep.</sub>
</div>
