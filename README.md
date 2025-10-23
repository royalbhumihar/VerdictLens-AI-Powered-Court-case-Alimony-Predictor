# ⚖️ VerdictLens  
### *AI-Powered Court Case Outcome Prediction and Alimony Evaluation System*

---

## 📘 Overview  
**VerdictLens** is an AI-powered decision-support system designed to assist in predicting **court case outcomes** and estimating **alimony or compensation** using advanced **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
It focuses on **family law cases** (divorce, maintenance, custody) by analyzing thousands of Indian court judgments to extract meaningful insights and predictions.

The system leverages **Large Language Models (LLMs)** and **Hugging Face transformers** for deep contextual understanding of legal documents, enabling it to capture complex judicial reasoning and predict outcomes more accurately.

---

## 🚀 Current Status  
> **Development Stage:** 🛠️ *In Progress*  
- Requirement analysis and data collection are complete.  
- Data preprocessing and LLM integration are ongoing.  
- Model training, regression-based alimony prediction, and frontend-backend integration are under active development.  

---

## 🎯 Objectives  
- Predict likely **court outcomes** using past judgments.  
- Estimate **alimony or compensation** based on financial and social parameters.  
- Provide a **transparent and explainable AI model** for judicial decision support.  
- Enable **data-driven insights** for legal researchers, advocates, and policymakers.  
- Integrate **LLMs and Hugging Face models** for enhanced contextual accuracy.

---

## 🧩 System Architecture  

1. **Data Collection & Processing**
   - Extracts and scrapes data from public legal repositories like *Indian Kanoon* and *eCourts*.
   - Performs OCR on scanned judgments and text cleaning.
   - Uses NLP techniques to extract entities like income, dependents, and case outcomes.

2. **Prediction & Evaluation**
   - Uses classification models for **outcome prediction**.
   - Employs regression and rule-based models for **alimony estimation**.
   - Incorporates *Legal-BERT*, *DistilBERT*, and other Hugging Face LLMs for deeper semantic analysis.

3. **User Interface (Planned)**
   - Intuitive dashboard built using **React.js** and **Node.js**.
   - Backend integrated with **Python (Flask/FastAPI)** ML microservices.
   - Case analytics visualization using **MongoDB** and **REST APIs**.

---

## 🧠 Tech Stack

| **Component** | **Technology Used** |
|----------------|---------------------|
| **Frontend** | React.js |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **ML/NLP** | Python (Scikit-learn, NLTK, SpaCy, XGBoost, BERT, DistilBERT) |
| **LLMs / Transformers** | Hugging Face (Legal-BERT, RoBERTa, GPT-based fine-tuned models) |
| **Deployment** | Docker, Flask/FastAPI |
| **Data Sources** | Indian Kanoon, eCourts, Hugging Face Legal Datasets |

---

## 📊 Data Sources & Pipeline

---
> 🧾 *VerdictLens represents a modern integration of legal intelligence, AI, and LLM-driven reasoning to make the judicial system more data-informed, transparent, and accessible.*


- **Primary Sources:**  
  - [Indian Kanoon](https://indiankanoon.org) — For case judgments and text-based rulings.  
  - [eCourts](https://ecourts.gov.in) — Official repository for Indian judiciary data.  
  - [Hugging Face Datasets](https://huggingface.co/datasets) — For legal-domain pre-trained corpora.  


- ## ⚙️ Data Pipeline Overview

[Raw Legal PDFs / HTML]
↓
[OCR + Text Extraction]
↓
[NLP Cleaning + Tokenization]
↓
[Feature Extraction (Income, Duration, Dependents)]
↓
[LLM Embedding via Hugging Face]
↓
[ML Models: Classification + Regression]
↓
[Outcome Prediction & Alimony Range]
↓
[Dashboard Visualization]


- ## 📈 SWOT Analysis

| **Strengths** | **Weaknesses** |
|----------------|----------------|
| Dual functionality (Outcome + Alimony) | Dependence on large dataset |
| Use of LLMs for high contextual accuracy | High GPU & computation cost |

| **Opportunities** | **Threats** |
|------------------|--------------|
| Integration with e-Courts / SUPACE | Data privacy & legal constraints |
| Adoption by law firms and legal startups | Algorithmic bias due to past judgments |

---

## 🏗️ Project Progress  

| **Phase** | **Status** |
|------------|------------|
| Requirement Analysis | ✅ Completed |
| Data Collection & Cleaning | ✅ Completed |
| Model Design (LLMs + Regression) | 🔄 In Progress |
| Dashboard Development | 🔄 Ongoing |
| Testing & Deployment | ⏳ Upcoming |

---

## 🧩 Future Scope  
- Extend prediction modules to **criminal and civil cases**.  
- Integrate **real-time data** from e-Court APIs.  
- Enhance explainability using **SHAP/LIME visualization tools**.  
- Develop **bias detection and fairness modules** for ethical compliance.  
- Expand to **regional language judgments** using multilingual transformers.  

---

## 📚 References  

1. Aletras, N., Tsarapatsanis, D., Preoţiuc-Pietro, D., & Lampos, V. (2016). *Predicting judicial decisions of the European Court of Human Rights.* [PeerJ Computer Science](https://peerj.com/articles/cs-93/)  
2. Bansal, P., & Kumar, S. (2020). *Application of AI in Indian Judicial System.* [IJLLJS – International Journal of Law, Language & Judicial Systems](https://ijlljs.in/)  
3. Katz, D. M., Bommarito, M. J., & Blackman, J. (2017). *Predicting the behavior of the Supreme Court of the United States.* [PLOS ONE](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0174698)  
4. Malik, A., & Mathur, R. (2021). *Predictive Analytics in Indian Judiciary.* [JILT – Journal of Indian Law and Technology](https://jilt.in/)  
5. Ministry of Law and Justice. (2022). *E-Courts Mission Mode Project Phase II.* [E-Courts Portal](https://ecourts.gov.in/ecourts_home/)  
6. Supreme Court of India. (2020). *SUPACE: Portal for Assistance in Courts Efficiency.* [Supreme Court of India](https://www.sci.gov.in)  
7. Chalkidis, I. et al. (2020). *Legal-BERT: The Muppets straight out of Law School.* [Hugging Face Research](https://huggingface.co/transformers/)  
8. OpenAI. (2024). *Large Language Models for Legal Reasoning and Judicial Analytics.*

---
