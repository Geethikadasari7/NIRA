<div align="center">

# 🌸 NIRA: Women's Menstrual Health Navigator

**Understand. Navigate. Prepare.**

[![Built with AWS PartyRock](https://img.shields.io/badge/Built%20with-AWS%20PartyRock-FF9900?style=for-the-badge&logo=amazonaws)](https://partyrock.aws/)
[![Hackathon](https://img.shields.io/badge/Hackathon-Women%20Who%20Master%202026-8A2BE2?style=for-the-badge)](https://www.aspireforher.com/)
[![Status](https://img.shields.io/badge/Status-MVP%20Live-brightgreen?style=for-the-badge)]()

*A private, multilingual AI health-navigation companion designed to bridge the gap between uncertainty and professional care.*

</div>



## 🚨 The Problem

Menstrual-health concerns are often accompanied by overwhelming uncertainty. When experiencing symptoms or changes, women frequently ask:
- *Is this normal?*
- *Should I be worried?*
- *When should I see a doctor?*
- *What should I even ask them?*

Traditional symptom checkers spit out terrifying medical jargon or misdiagnose, causing anxiety. **NIRA focuses on the uncertainty surrounding the symptom—not on diagnosing the symptom itself.**



## 💡 Our Solution: The NIRA Navigation Layer

NIRA acts as a **navigation layer** between a user's health uncertainty and professional medical care. We don't diagnose; we empower.

<div align="center">

| Traditional Approach ❌ | NIRA's Approach ✅ |
| :--- | :--- |
| **"What disease do I have?"** | **"What should I understand?"** |
| Diagnosis-focused | Navigation-focused |
| Information overload | Action-oriented guidance |
| Generic, anxiety-inducing answers | Tailored consultation preparation |
| Symptom ➔ Diagnosis | Uncertainty ➔ Understanding ➔ Next Step |

</div>

### ✨ Key Features

- 🧠 **Plain-Language Understanding:** Translates complex health data into simple, digestible explanations.
- 🛡️ **Safety-First Navigation:** Classifies the best next step (Monitor, Consult a Doctor, or Seek Urgent Care).
- 📝 **Consultation Preparation:** Generates a personalized "Consultation Card" with exact questions to ask the doctor.
- 📊 **Symptom Tracking Guide:** Highlights exactly what patterns the user should track before their appointment.
- 🌐 **Multilingual & Accessible:** Supports English, Simple English, and Regional Languages (e.g., Telugu) for maximum inclusivity.


## 🏗️ Architecture & GenAI Workflow

NIRA is built iteratively on **AWS PartyRock**, utilizing prompt-chaining to ensure safety, accuracy, and clear outputs.

```mermaid
graph TD
    %% Styling
    classDef user fill:#e1bee7,stroke:#8e24aa,stroke-width:2px,color:black
    classDef ai fill:#bbdefb,stroke:#1976d2,stroke-width:2px,color:black
    classDef guard fill:#ffcc80,stroke:#f57c00,stroke-width:2px,color:black
    classDef output fill:#c8e6c9,stroke:#388e3c,stroke-width:2px,color:black

    %% Nodes
    A[👤 User Input: Minimum Necessary Information]:::user
    B[🧠 AWS PartyRock: GenAI Processing]:::ai
    C{🛡️ Safety Guardrails & Prompt Layer}:::guard
    
    D[📖 Plain-Language Explanation]:::output
    E[🧭 Next-Step Classification]:::output
    F[📝 Doctor Consultation Card]:::output
    G[🚨 Standard Medical Disclaimer]:::guard

    %% Flow
    A -->|Text/Voice Input| B
    B --> C
    
    C -->|Safe / Informational| D
    C -->|Safe / Informational| E
    C -->|Safe / Informational| F
    
    C -->|Diagnostic Query Detected| G
    
    D -.-> H((Actionable Understanding))
    E -.-> H
    F -.-> H
```

## 📜 Declaration of Originality

I, **Geethika Dasari**, hereby declare that this project, **NIRA**, submitted for the Aspire For Her × Logitech Women Who Master Hackathon 2026, is entirely my own original work. All application logic, prompts, presentation materials, and documentation were completed individually during the official hackathon window, and no unauthorized assistance was used.

📧 **Contact:** [geethikaadasari@gmail.com](mailto:geethikaadasari@gmail.com)
