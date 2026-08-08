<div align="center">

# 🌸 NIRA: Women's Menstrual Health Navigator

**Understand. Navigate. Prepare.**

[![Built with AWS PartyRock](https://img.shields.io/badge/Built%20with-AWS%20PartyRock-FF9900?style=for-the-badge&logo=amazonaws)](https://partyrock.aws/)
[![Hackathon](https://img.shields.io/badge/Hackathon-Women%20Who%20Master%202026-8A2BE2?style=for-the-badge)](https://www.aspireforher.com/)
[![Status](https://img.shields.io/badge/Status-MVP%20Live-brightgreen?style=for-the-badge)]()

*A private, multilingual AI health-navigation companion designed to bridge the gap between uncertainty and professional care.*

</div>

---

## 🚨 The Problem

Menstrual-health concerns are often accompanied by overwhelming uncertainty. When experiencing symptoms or changes, women frequently ask:
- *Is this normal?*
- *Should I be worried?*
- *When should I see a doctor?*
- *What should I even ask them?*

Traditional symptom checkers spit out terrifying medical jargon or misdiagnose, causing anxiety. **NIRA focuses on the uncertainty surrounding the symptom—not on diagnosing the symptom itself.**

---

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

---

## 🏗️ Architecture & GenAI Workflow

NIRA is built iteratively on **AWS PartyRock**, utilizing prompt-chaining to ensure safety, accuracy, and clear outputs.

*(Upload your generated architecture diagram to your repo and update the image path below)*
<div align="center">
  <img src="./docs/architecture.png" alt="NIRA Architecture Diagram" width="800"/>
</div>

### How Information Flows:
1. **User Input:** User shares minimum necessary symptoms/concerns (Text/Voice).
2. **GenAI Processing Layer:** AWS GenAI synthesizes the input against medical knowledge guidelines.
3. **Safety Guardrails:** Strict instructions prevent the AI from diagnosing or prescribing. 
4. **Actionable Output:** 
   - Plain-Language Explanation
   - Next-Step Classification
   - Doctor Consultation Card

---

## 💼 Business Model & Future Scalability

While the current MVP focuses on the core AI navigation, NIRA is designed to scale into a self-sustaining Women's Health Platform:

- 🛍️ **NIRA MedivAI Store:** A curated marketplace for trusted women's wellness, hygiene, and menstrual health products.
- 👩‍⚕️ **Doctor Appointments:** Seamless discovery and direct appointment booking with verified gynecologists and specialists.
- ⭐ **NIRA+ Premium:** Advanced long-term cycle tracking, personalized insights, and priority tele-consultations.
- 🤝 **B2B Partnerships:** Collaborations with rural healthcare NGOs, clinics, and women's-health initiatives.

---

## 🛡️ Responsible AI & Safety

NIRA is engineered with strict healthcare safety boundaries:
- **Zero Diagnosis:** NIRA explicitly states it is not a doctor.
- **Data Privacy:** Minimum-information approach; no unnecessary sensitive data is collected.
- **Human Oversight:** AI-generated guidance is purely informational. All medical decisions remain with qualified healthcare professionals.

---

## 🚀 Live Prototype

Try the working MVP built for the hackathon:
🔗 **[Launch NIRA on AWS PartyRock](https://partyrock.aws/u/geethikadasari/rVxVouJms7/NIRA-Women's-Menstrual-Health-Navigator/)**

---

## 👩‍💻 Team Daredevils

Built with ❤️ for the **Aspire For Her × Logitech: Women Who Master Hackathon 2026**.

**Project Lead:** Geethika Dasari  
**Vision:** *Less uncertainty. More understanding. Better next steps.*

> **Disclaimer:** NIRA is an AI-powered health-navigation prototype intended to support understanding and preparation. It is not a medical diagnostic tool and should not be used as a substitute for professional medical advice, diagnosis, or treatment.
