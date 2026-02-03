# Nomads — Climate Change × Gender Inequality  
### NASA Space Apps Challenge 2024

**Nomads** is an interactive web platform developed for the **2024 NASA Space Apps Challenge** that explores the **interconnected relationship between climate change and gender inequality** using global datasets, local case studies, and interactive visualizations. The project was awarded a Global Nominee award - selected out of 15,000+ participants, the top 6% globally. 

🌍 **Live Project:** https://www.nomads-nasa.earth/  
🚀 **NASA Space Apps Team Page:** https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/nomads/?tab=project  
🎥 **Project Demonstration:** https://www.canva.com/design/DAGSyXBF_P4/1waTQ18rlFQyufRSZ-1Dbw/view

---

## Project Summary

Climate change and gender inequality are two of the most pressing global challenges of our time. Rather than treating them as separate issues, **Nomads** approaches them as **deeply interconnected problems** that must be addressed together to achieve sustainable and equitable progress.

We built an interactive, educational web platform that helps users understand **how climate vulnerability disproportionately affects gender equality**, both globally and locally, through data-driven storytelling and interactive decision-making.

---

## What We Built

Nomads integrates multiple components into a single interactive experience:

### 🌐 Global Data Visualization
- Modeled and visualized **climate vulnerability** (ND-GAIN Index) and **gender inequality** (UNDP Gender Inequality Index)
- Covers **188 countries over a 27-year period**
- Interactive **heat maps**, **scatter plots**, and **time sliders** allow users to explore trends across time and regions

### 🌍 Interactive 3D Globe
- A fully interactive **3D globe** enabling users to:
  - rotate and zoom
  - select countries
  - track changes in climate vulnerability and gender inequality over time

### 📍 Local Case Studies
To move beyond global averages, we analyzed **five real-world climate events** and their gendered impacts, including:

- **Typhoon Haiyan (Philippines, 2013)**  
  After the disaster, reported rape rates increased from **5 to 9**, highlighting the vulnerability of women and girls in post-disaster contexts.

Each case study includes:
- event background
- gender-related impacts
- supporting statistics
- NASA satellite imagery where applicable

### 🧭 Country-Specific Solutions
- Action plans for **12 countries**, drawing from expert sources such as:
  - Climate Change Gender Action Plans (ccGAPs)
  - IUCN Regional Conservation Forum (RCF)
- Designed to encourage informed, localized action

### 🎮 Interactive Policy Game
- Users act as policymakers making real-world decisions
- Choices affect:
  - Gender Inequality Index (GII)
  - violence rates
  - overall societal well-being
- Outcomes are **data-backed** and grounded in research
- Includes visual feedback and NASA satellite imagery

---

## Why This Matters

- **Educational Impact:**  
  Makes complex global issues accessible and engaging for teens and adults

- **Actionable Insights:**  
  Encourages evidence-based thinking and policy awareness

- **Global + Local Perspective:**  
  Combines large-scale data with concrete human impacts

By showing that **climate change and gender inequality reinforce each other**, Nomads demonstrates why addressing them together is more effective than tackling them in isolation.

---

## How It Works (Technical Overview)

### Data Processing & Visualization
- Climate vulnerability data: **ND-GAIN Index**
- Gender inequality data: **UNDP Gender Inequality Index (GII)**
- Data cleaned and processed using **Python (pandas, numpy)**
- Visualized using interactive charts and maps

### Frontend & Visualization
- **React** for frontend architecture
- **JavaScript, HTML, CSS**
- Interactive **3D globe visualization** (`react-globe.gl`)
- Dynamic charts with time sliders

---

## Use of Artificial Intelligence (AI)

AI tools were used **only for media and presentation**, not for data analysis:

- **MidJourney** — image generation
- **Dream Machine** — image animation
- **UDIO** — background music
- **ElevenLabs** — voiceover narration

---

## Data & Sources

### NASA & Space Agency Data
- NASA Earth Observatory imagery

### Climate & Gender Data Sources
- ND-GAIN Climate Vulnerability Index
- UNDP Gender Inequality Index (GII)
- World Bank Group
- UNICEF
- UN Women
- UNODC
- IOM Migration
- World Health Organization
- United Nations
- ReliefWeb
- Brookings
- BMJ
- CNN

### Case Study & Policy Sources
- Philippines: Super Typhoon Haiyan (Yolanda) — Humanitarian Impact Reports
- Climate Change Gender Action Plans (ccGAPs)
- TEAM LEWIS Foundation (2022)

---

## My Role (Fork Owner)

**Nurkyz Ydyrysova — Team Lead**

Responsibilities included:
- overall project direction and coordination
- research and validation of climate–gender case studies
- sourcing and organizing datasets
- structuring the platform narrative and user flow
- preparation of final submission materials and demo

> This repository represents a **team effort**. Code contributions are credited in the original repository and team documentation.

---

## Running the Project Locally

```bash
npm install
npm start
