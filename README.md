# CareScribe — Documentation Intelligence Research
### Founder-led research into documentation risk in UK adult social care.

CareScribe is an early-stage research project exploring documentation risk patterns in UK adult social care. The focus is on understanding how small narrative gaps in care records can evolve into compliance risks during inspections, safeguarding reviews, and internal audits.

In regulated environments overseen by the **Care Quality Commission (CQC)**, documentation is not just administrative—it is the primary evidence of care delivery and decision-making.

---

## 🔍 The Problem Being Explored
In day-to-day care environments, documentation is completed under extreme time pressure. As a result, subtle narrative gaps emerge:
*   **Missing follow-up actions** mentioned verbally but not recorded.
*   **Incomplete incident outcomes** (e.g., "Resident fell" with no "Resident is now stable").
*   **Lack of contextual detail** in observations.
*   **Weak links** between behavioral events and care plans.

> **The Core Question:** How many compliance risks are actually *documentation visibility* problems rather than *care delivery* problems?

---

## 🚀 Simulation Prototype
An early-stage simulation has been built to explore how documentation risk flags might work in practice.
*   **Live Simulation:** [CareScribe Simulation Link](https://carescribe-flow-sim.bubbleapps.io)
*   **Status:** No production system is being built at this stage. The focus is on understanding the problem deeply before designing solutions.

---

## 📂 Repository Structure
*   **[/foundations/](./foundations/)** 
    *   `problem-statement.md` → Defines the core documentation challenges.
*   **[/simulation/](./simulation/)**
    *   `logic-rules.md` → Defines structured signals for identifying gaps.
    *   `scenarios.md` → Simulated care notes used to test detection logic.
*   **[/validation/](./validation/)**
    *   `tester-script.md` → Observations from conversations and usability tests.
*   **[/insights/](./insights/)**
    *   `false-assumptions.md` → Incorrect assumptions identified during research.

---

## 💡 Why This Matters
In adult social care, **good care must be visible in documentation.** When records lack clarity, reviewers cannot fully understand what actions were taken and why. This creates risk—not necessarily because care was poor, but because the *evidence* of care is incomplete.

### Current Focus:
*   Running structured usability conversations with care professionals.
*   Testing whether documentation gaps can be detected through simple logic patterns.
*   Understanding where documentation workflows break under real-world pressure.

---

## 🤝 Contributing / Sharing Insight
If you work in adult social care and have experience with **inspections, audit preparation, or safeguarding**, your perspective is valuable. This project is built through real-world insight, not assumptions.

### Project Status:
*   ✅ Early-stage research
*   ⚠️ No production deployment
*   🎯 Focused on validation, not scale

---

## 🏗️ Conceptual System Flow (Early Simulation)
![CareScribe Architecture](./carescribe-architecture.png)

## About
[www.protolq.com](https://protolq.com)
