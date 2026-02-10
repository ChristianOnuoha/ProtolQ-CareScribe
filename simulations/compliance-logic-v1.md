# 📑 CareScribe: Compliance Logic Engine (v1)

**Framework:** CQC Regulation 17 — Good Governance  
**Focus:** Mitigating "Narrative Risk" and "Visibility Voids"

---

## 1. The Core Logic: Objective vs. Subjective
The CareScribe engine identifies **Subjective Phrases** (Audit Risks) and prompts for **Objective Evidence** to strengthen compliance.

| Input Category | Subjective Trigger (High Risk) | CareScribe Intelligence Prompt | Objective Requirement (CQC Aligned) |
| :--- | :--- | :--- | :--- |
| **Wellbeing** | "Client had a good day." | 🚩 **Flag:** Vague descriptor. | Specific mood, engagement level, or appetite metrics. |
| **Safety** | "Safe transfer to chair." | 🚩 **Flag:** Process missing. | Equipment used (e.g., Hoist), skin check, and client pain report. |
| **Medication** | "Meds taken fine." | 🚩 **Flag:** Verification missing. | Dosage confirmed, MAR signature, and observed side effects. |
| **Hydration** | "Drank plenty of water." | 🚩 **Flag:** Quantifiable risk. | Exact volume (ml) and output/refusal notes. |

---

## 2. Risk Detection: The "Silent Omission"
CareScribe logic triggers a **Compliance Flag** when a mandatory clinical audit trail is broken.

### **Example: PRN (As Needed) Medication**
*   **Standard Entry:** *"Gave PRN for agitation."*
*   **CareScribe Intelligence Check:**
    1.  **Identify:** PRN administered.
    2.  **Logic Check:** Is there a pre-administration justification? (e.g., *"Tried distraction first"*).
    3.  **Logic Check:** Is there a post-administration outcome? (e.g., *"Settled after 30 mins"*).
*   **Result:** **Gap Found.** Missing the "Alternative Intervention" step required by CQC for restrictive practice monitoring.

---

## 3. The "Visibility Void" Filter
Designed specifically for **Agency and Third-Party Staff** to maintain institutional memory and consistency.

*   **Logic Rule:** If the staff member is identified as "Agency/New," the **Detail Threshold** is automatically increased.
*   **Rationale:** While permanent staff may intuitively know a client's baseline, an auditor requires documented proof that a rotating worker has verified that baseline during their specific shift.

---

## 4. Simulation Test Case: Pressure Area Care
**Input:** *"Turned client. They are okay."*

🚩 **CareScribe Logic Flag:** Potential [CQC Regulation 17](https://www.cqc.org.uk) Violation.

**Required Logic Prompts:**
1.  **Positioning:** What was the specific position (Left, Right, Supine)?
2.  **Clinical Check:** Was skin integrity verified at all pressure points?
3.  **Observation:** Is there any new redness or Grade 1 pressure damage?

**Output:** A high-integrity narrative proving the agency is actively and systematically monitoring skin health.
