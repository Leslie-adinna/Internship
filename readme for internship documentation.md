
# 🩺 Pediatric Pulmonology Chatbot – AI Internship Documentation

## 🎓 Internship Overview
**Program:** 3-Month Internship in Artificial Intelligence  
**Domain:** AI for Healthcare  
**Focus:** Data Gathering, NLP, and Conversational AI  
**Duration:** April 2025 – July 2025  
**Host Organization:** Omeife Technology  
**Supervisor:** Mrs. Peace Okafor  

---

## 🚀 Project Summary
This internship focused on building a clinical decision-support chatbot for **Pediatric Pulmonology** using advanced **Natural Language Processing (NLP)** and **AI models**. The chatbot is designed to help caregivers, patients, and healthcare professionals with accurate, symptom-based Q&A, triage, and clinical education.

---

## 📌 Responsibilities

### 🗂 Medical Data Collection & Curation
- Collected disease information from **trusted medical websites**, including:
  - [Mayo Clinic](https://www.mayoclinic.org)
  - [Cleveland Clinic](https://my.clevelandclinic.org/health)
  - [Medscape](https://www.medscape.com)
  - [PubMed](https://pubmed.ncbi.nlm.nih.gov)
  - [WHO](https://www.who.int)
  - [CDC](https://www.cdc.gov)
  - [American Academy of Pediatrics](https://www.aap.org)
  - [GINA - Global Initiative for Asthma](https://ginasthma.org)
  - [American Orthopedic Society for Sports Medicine (AOSSM)](https://www.sportsmed.org)
  - [AAOS - American Academy of Orthopedic Surgeons](https://www.aaos.org)

- Focused on diseases in:
  - Pediatric pulmonology
  - Cardiology
  - Hematology
  - Oncology
  - Immunology

---

## 🧠 Knowledge Extraction
Used **NLP techniques** and **regex-based rules** to extract:
- ✅ Definition
- ✅ Symptoms
- ✅ Causes
- ✅ Risk factors
- ✅ Diagnosis & tests
- ✅ Treatment & prevention
- ✅ Complications
- ✅ Differential diagnosis
- ✅ Drug information & side effects
- ✅ Epidemiology

Developed **structured Q&A datasets** and **doctor-patient conversation samples**.

---

## 🧪 Model Building

### 1️⃣ TextCatBoW – spaCy
- Used `textcat_bow` from **spaCy** for query classification.
- Categories: Symptoms, Causes, Treatment, Prevention, Emergency
- Fast inference, suitable for rule-based modules.

### 2️⃣ BioGPT – Microsoft Biomedical LLM
- Integrated [BioGPT](https://huggingface.co/microsoft/BioGPT) for generative medical reasoning.
- Answered free-form clinical questions with high accuracy and relevance.
- Used in hybrid mode with Q&A matching for better contextual responses.

---

## 🧬 Entity Recognition
- Used **spaCy** and **SciSpaCy** for biomedical NER.
- Recognized diseases, medications, symptoms, procedures, anatomy.

---

## 💬 Gradio Chatbot Interface
- Built a user-friendly chatbot interface using **Gradio**.
- Supported multi-turn conversations and follow-up logic.
- Integrated BioGPT for dynamic medical reasoning.
- Simulated real-time doctor-patient interactions.

---

## 🧰 Tools & Technologies
| Category | Tools |
|---------|-------|
| Programming | Python |
| NLP & AI | spaCy, SciSpaCy, Transformers, BioGPT |
| Interfaces | Gradio |
| Modeling | scikit-learn, Sentence Transformers |
| Utilities | Pandas, Regex, BeautifulSoup |
| Deployment | Git, GitHub, Google Colab |

---

## ✅ Outcome
A fully functional pediatric pulmonology chatbot prototype capable of:
- Understanding user symptoms
- Extracting relevant medical context
- Providing trusted responses using hybrid AI methods

---

## 💭 Reflection
This internship helped me develop a strong foundation in:
- Real-world medical data curation
- Conversational AI and LLM integration
- Responsible and ethical AI in healthcare

> **Built for Impact. Trained for Excellence. Focused on Health.**

---

🖊 **Intern:** LESLIE EL  
📅 Duration: April – July 2025  
