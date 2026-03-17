# Simulation Test Cases — CareScribe

This document contains simulated care documentation examples used to test the early risk flag logic within the **CareScribe research project**. 

The goal is to explore whether structured logic can help identify potential **narrative gaps** in documentation before records are finalized. These examples reflect common documentation scenarios observed in adult social care environments.

---

## 🧪 Test Case 1: Incident Without Outcome
**Care Note:**
> *"Resident became agitated during evening routine and shouted at staff members. Staff intervened to calm the situation."*


| Feature | Description |
| :--- | :--- |
| **Potential Gap** | Does not clarify if the resident settled, if monitoring was required, or if follow-up occurred. |
| **Risk Flag** | `Missing Outcome Documentation` |
| **Why it Matters** | During an audit, documentation must show how a situation concluded to prove it was safely resolved. |

---

## 🧪 Test Case 2: Fall Without Escalation
**Care Note:**
> *"Resident fell near the corridor outside their room at approximately 14:30. Staff assisted the resident back to their chair."*


| Feature | Description |
| :--- | :--- |
| **Potential Gap** | No mention of injury checks, whether a senior was informed, or if health professionals/family were contacted. |
| **Risk Flag** | `Escalation Gap` |
| **Why it Matters** | When a fall occurs, inspectors look for evidence that safeguarding and medical protocols were triggered. |

---

## 🧪 Test Case 3: Observation Without Context
**Care Note:**
> *"Resident appeared distressed during lunchtime."*


| Feature | Description |
| :--- | :--- |
| **Potential Gap** | Doesn't explain the specific behavior, whether support was offered, or if this is a known pattern in the care plan. |
| **Risk Flag** | `Context Deficiency` |
| **Why it Matters** | Observational notes need context so future reviewers can understand the resident's specific needs and the staff's response. |

---

## 🧪 Test Case 4: Medication Refusal
**Care Note:**
> *"Resident refused medication during morning round."*


| Feature | Description |
| :--- | :--- |
| **Potential Gap** | No indication if it was offered again, if it follows the management plan, or if a senior was notified. |
| **Risk Flag** | `Care Plan Link Missing` |
| **Why it Matters** | Medication refusals are high-risk; documentation must prove that monitoring and procedures were strictly followed. |

---

## 🧪 Test Case 5: Repetitive Narrative
**Care Plan Review Entry:**
> *"Resident stable. No changes observed this month."* (Repeated across several monthly reviews).


| Feature | Description |
| :--- | :--- |
| **Potential Gap** | Fails to show progress toward care goals or involvement of the resident/family in the review process. |
| **Risk Flag** | `Repetitive Narrative Pattern` |
| **Why it Matters** | "Boilerplate" notes suggest a lack of active, person-centered evaluation, which is a major red flag for CQC/inspectors. |

---

## 🎯 Simulation Purpose
These test cases support conversations with care professionals regarding:
1. How documentation gaps occur in high-pressure workflows.
2. Which omissions create the highest **compliance risk**.
3. Whether structured review support adds value to real-world care teams.

*This project is currently in the **validation and research phase**. These examples are used purely for exploration and discussion.*
