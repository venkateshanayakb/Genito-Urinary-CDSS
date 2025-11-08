# Genito-Urinary Clinical Decision Support System (CDSS)

## 🩺 Project Overview
This repository hosts a **Clinical Decision Support System (CDSS)** focused on **Genito-Urinary (GU) infections**, designed to assist clinicians in structured diagnosis and reasoning.  
The system uses a logic-based conversational flow inspired by clinical examination principles — *Ask, Inspect, Palpate, Lock, Listen, Check, and Measure* — and references the **IKP-BTP Algorithm** alongside a curated **Knowledge Bank (P-GU series)**.

---

## 🎯 Objectives
- To provide a **logic-driven clinical chatbot** that guides step-by-step GU diagnosis.
- To **standardize** the reasoning pathway for evaluating male and female GU symptoms.
- To demonstrate how **AI-driven dialogue systems** can support **Ayurvedic and modern medical diagnosis**.

---

## 🧩 Key Features
- **Dynamic patient dialogue** – asks and adapts based on responses.  
- **Demographic stratification** – incorporates Name, Age, and Gender to tailor logic for men and women.  
- **Algorithm-based reasoning** – follows the **IKP-BTP** diagnostic framework.  
- **Structured workflow** – integrates *Ask → Inspect → Palpate → Lock → Listen → Check → Measure*.  
- **Explainable output** – provides diagnostic summary, reasoning, and next-step suggestions.  

---

## 🧠 Knowledge Sources
All medical insights are derived from:
- Knowledge bank files labeled **P-GU-00x**, curated from validated references.
- Diagnostic flow modeled from **IKP-BTP Algorithm** (PDF).
- Standard genito-urinary clinical protocols.

---

## ⚙️ Workflow Overview

| Stage | Description |
|--------|--------------|
| **Ask** | Collect patient history, symptoms, and onset. |
| **Inspect** | Observe external findings (redness, swelling, lesions). |
| **Palpate** | Document examination findings (tenderness, lumps). |
| **Lock** | Identify key diagnostic “locks” (critical decision points). |
| **Listen** | Incorporate additional patient-reported clues. |
| **Check** | Include test findings (urinalysis, culture, imaging). |
| **Measure** | Quantify vital parameters (temperature, urine output, etc.). |

---

## 🧮 Example Conversation Flow

**AI:** Please enter patient details — Name, Age, and Gender.  
**User:** Name: Ramesh, Age: 42, Gender: Male.  
**AI:** Thank you. What is the main urinary complaint (burning, frequency, discharge, pain, etc.)?  
**User:** Burning and increased frequency for 3 days.  
**AI:** Understood. Any associated fever, flank pain, or discharge?  
**User:** Mild fever, no discharge.  
**AI:** Based on current information, differential diagnoses include *Acute Cystitis* and *Urethritis*. Please confirm if any lower abdominal pain is present.  

---

## 🧰 Tech Stack
- **Google AI Studio** – for chatbot prompt design and flow logic.
- **GitHub** – for version control and project sharing.
- *(Optional)* Future expansion: Python / Flask backend for integration with EMR or web interface.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<yourusername>/Genito-Urinary-CDSS.git
