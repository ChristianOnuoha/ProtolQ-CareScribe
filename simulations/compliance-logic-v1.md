# 📑 CareScribe Compliance Logic Engine (v1)

**Framework:** [CQC Regulation 17 — Good Governance](https://www.cqc.org.uk)  
**Focus:** Mitigating "Narrative Risk" and "Visibility Voids"

---

## ⚖️ CQC Regulation 17: Core Evidence Requirements

These four pillars represent the "North Star" for the Narrative Gap logic. Every feature in the simulation should map back to at least one of these points.

1. **Systemic Oversight**
   - **Goal:** Move beyond spotting individual errors to monitoring agency-wide quality.
   - **Logic Requirement:** Provide a high-level view of documentation health across all care notes.
2. **Auditable Trail**
   - **Goal:** Zero "silent deletions."
   - **Logic Requirement:** Maintain clear records of who flagged a note, what was changed, and the timestamp of the intervention.
3. **Risk Mitigation**
   - **Goal:** Close the loop on clinical safety.
   - **Logic Requirement:** Identify a risk (e.g., a missed meal) and ensure the documentation records the specific action taken.
4. **Continuous Improvement**
   - **Goal:** Demonstrable progress in care quality.
   - **Logic Requirement:** Generate trends showing that the "Narrative Gap" logic is reducing documentation errors over time.

> [!TIP]
> **Founder Note:** Use these points during Week 6 sales conversations to demonstrate how this tool automates CQC Compliance.

---

## 1. The Core Logic: Objective vs. Subjective

The CareScribe engine identifies **Subjective Phrases** and prompts for **Objective Evidence**.

| Input Category | Subjective Trigger (High Risk) | CareScribe Intelligence Prompt | Objective Requirement (CQC Aligned) |
| :--- | :--- | :--- | :--- |
| **Wellbeing** | "Client had a good day." | 🚩 **Flag:** Vague descriptor. | Specific mood, engagement, or appetite. |
| **Safety** | "Safe transfer to chair." | 🚩 **Flag:** Process missing. | Equipment (Hoist), skin check, pain report. |
| **Medication** | "Meds taken fine." | 🚩 **Flag:** Verification missing. | Dosage, MAR signature, observed side effects. |
| **Hydration** | "Drank plenty of water." | 🚩 **Flag:** Quantifiable risk. | Exact volume (ml) and output/refusal notes. |

---

## 2. Risk Detection: The "Silent Omission"

CareScribe logic triggers a **Compliance Flag** when a mandatory clinical audit trail is broken.

### **Example: PRN (As Needed) Medication**
*   **Standard Entry:** *"Gave PRN for agitation."*
*   **CareScribe Intelligence Check:**
    - [ ] **Identify:** PRN administered.
    - [ ] **Logic Check:** Is there a pre-administration justification? (e.g., *"Tried distraction first"*).
    - [ ] **Logic Check:** Is there a post-administration outcome? (e.g., *"Settled after 30 mins"*).
*   **Result:** **Gap Found.** Missing the "Alternative Intervention" step required by CQC Restrictive Practice monitoring.

---

## 3. The "Visibility Void" Filter

Designed specifically for **Agency and Third-Party Staff** to maintain consistency.

*   **Logic Rule:** If staff is "Agency/New," the **Detail Threshold** is automatically increased.
*   **Rationale:** Auditors require proof that rotating workers have verified the client's baseline during their specific shift.

---

## 4. Simulation Test Case: Pressure Area Care

**Input:** *"Turned client. They are okay."*

🚩 **CareScribe Logic Flag:** Potential CQC Regulation 17 Violation.

**Required Logic Prompts:**
*   **Positioning:** Specific position (Left, Right, Supine)?
*   **Clinical Check:** Skin integrity verified at all pressure points?
*   **Observation:** Any new redness or Grade 1 pressure damage?
