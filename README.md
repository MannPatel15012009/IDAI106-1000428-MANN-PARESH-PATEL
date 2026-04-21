# MindPod – AI‑Powered Mindfulness App

[![Figma Prototype](https://img.shields.io/badge/Figma-Interactive_Prototype-FF7262?logo=figma&logoColor=white)](https://www.figma.com/make/2XZkul2ZDN9A9TPPhA6Kjy/Interactive-App-Prototype?t=t8sAYddWYqeE8LmN-20&fullscreen=1)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
**Objective:** To help working professionals and interns manage workplace stress through brief, guided relaxation sessions triggered by real‑time stress indicators and user behaviour.  
**Target Audience:** Corporate employees, interns, and managers across age groups (16–64) who experience decision fatigue, performance anxiety, or burnout.  
**Scenario Context:** A mobile‑first application that integrates into a busy workday, offering AI‑suggested micro‑interventions (breathing, grounding, journaling) without disrupting workflow.

---

## 🧠 Design Thinking Overview

### 1️⃣ Empathize & Define

**Research Insights:**  
We conducted 12 in‑depth empathy interviews and created detailed personas. Key findings show that stress manifests differently: early‑career professionals need confidence boosts, while senior executives require discreet, low‑effort resets.

**10+ Personas (Included in `/Docs/Research/`):**

| Persona | Age | Role | Core Stress Trigger |
|---------|-----|------|---------------------|
| Vikram | 48 | Operations Head | High‑stakes decision fatigue |
| Ananya | 19 | HR Intern | Fear of mistakes / evaluation |
| Rajiv | 64 | Senior Consultant | Mental fatigue, tech complexity |
| Rohan | 24 | Software Developer | Workload & skipping breaks |
| Priya | 58 | HR Director | Change & information overload |
| Aarav | 16 | Intern | Lack of confidence |
| Meera | 38 | Finance & Parent | Time pressure / self‑care neglect |
| Dev | 27 | Sales Executive | Rejection & emotional exhaustion |
| Rahul | 42 | Project Manager | Multitasking & mental switch‑off |
| Sneha | 30 | UX Designer | Perfectionism & overthinking |
| Karan | 52 | Investment Analyst | High‑risk analysis paralysis |
| Neha | 35 | IT Team Lead | Team pressure & ignored own stress |

**Problem Statements (Extracted):**
- *Vikram* needs a way to recognise rising stress and take short, effective breaks without interrupting workflow.
- *Ananya* needs quick, simple techniques to calm down during stressful moments and regain confidence.
- *Rajiv* needs an effortless way to relax without navigating complex systems.
- … (complete list available in `Docs/Research/User_Personas.pdf`)

### 2️⃣ Ideate – Key Features

We defined **5 compulsory features** for each of the two primary user scenarios:  
*(A) High‑Pressure Decision Maker & (B) Anxious Early‑Career Professional*

| Scenario | Feature 1 | Feature 2 | Feature 3 | Feature 4 | Feature 5 |
|----------|-----------|-----------|-----------|-----------|-----------|
| **A: Vikram (Exec)** | AI Stress Pod Suggestion | 90‑sec Guided Breath | Minimal‑UI "Quiet Mode" | Passive Data‑Backed Calming | Stress Pattern Dashboard |
| **B: Ananya (Intern)** | Confidence‑Booster Prompts | Grounding Exercises | Quick Journal for Overthinking | Validation Check‑in | Calm Environment Visuals |

### 3️⃣ Prototype

The interactive prototype was built in **Figma** and includes the following implemented screens:

- 🏠 **Home Dashboard:** Clear entry point with "Start Session" button.
- 🤖 **Pod Section (AI Suggestion):** Context‑aware recommendation card (e.g., "You seem tense. Try 2 min breathing.").
- 🧘 **Relaxation Screen:** Guided animation with simple instructions.
- 📝 **Journal:** Minimal text entry for thought dumping.
- 📊 **Stress Dashboard:** Visual feedback on calm sessions completed.

👉 **[Launch Interactive Prototype (Figma Make)](https://www.figma.com/make/2XZkul2ZDN9A9TPPhA6Kjy/Interactive-App-Prototype?t=t8sAYddWYqeE8LmN-20&fullscreen=1)**

### 4️⃣ Test – User Feedback & Iterations

We tested the low‑fidelity wireframes with 6 users. The feedback is documented in `/Docs/Testing/User_Reviews_Report.xlsx`.

**Resulting Improvements:**
- Refined Home Dashboard layout for quicker orientation.
- Enhanced visibility of the AI Suggestion "Pod".
- Added reassuring microcopy for first‑time users.
---

## 🛠️ Technologies & Tools Used

| Category | Tools |
|----------|-------|
| **UI/UX Design & Prototyping** | Figma, Figma Make |
| **Research & Empathy Mapping** | Miro (digital whiteboard), Canva (persona cards) |
| **Data Analysis** | Microsoft Excel, CSV export |
| **Documentation** | Markdown, PDF Export |
| **Version Control** | Git & GitHub |

---

## 🎥 Demo & Screenshots

### 📸 UI Screenshots (from Wireframes folder)

| Home Dashboard | AI Suggestion Pod | Relaxation Screen |
|----------------|-------------------|-------------------|
| ![Home](Wireframes/Screenshots/home_dashboard.png) | ![Pod](Wireframes/Screenshots/pod_suggestion.png) | ![Relax](Wireframes/Screenshots/relaxation_screen.png) |

| Journal Entry | Stress Dashboard |
|---------------|------------------|
| ![Journal](Wireframes/Screenshots/journal_entry.png) | ![Dashboard](Wireframes/Screenshots/stress_dashboard.png) |

### 🎬 Demo Walkthrough

*Click the image below to view the Figma prototype walkthrough (recorded demo).*  
[![Watch Demo](https://img.shields.io/badge/Watch_Demo-Figma-0AC97F?style=for-the-badge&logo=figma)](https://www.figma.com/make/2XZkul2ZDN9A9TPPhA6Kjy/Interactive-App-Prototype?t=t8sAYddWYqeE8LmN-20&fullscreen=1)

> *Note: The prototype is fully clickable. Navigate using the hotspots to experience the flow.*

---

## 📂 Folder Details & Deliverables

- **`/Docs`** – Contains `Empathy_Maps.pdf`, `User_Personas.pdf`, and `Problem_Statements_Summary.md`. All 12 personas and detailed empathy maps are included.
- **`/Wireframes`** – Screenshots and exported prototype flows. High‑fidelity mockups for both scenarios.
- **`/Data`** – `User_Testing_Data.csv` converted from the Excel review sheet, ready for further analysis.

---

## 🤝 Contributing

This repository serves as a design case study. If you have suggestions for improving accessibility or user flow, please open an issue.

---

## 📄 License

This project is licensed under the MIT License.
