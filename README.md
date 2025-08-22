# health-symptom-checker-AI-IBM
Agentic AI Health Symptom Checker using IBM Granite + RAG (Hackathon Project)

# Topic: Agentic AI Health Symptom Checker  

## Project Overview  
The **Agentic AI Health Symptom Checker** is an AI-powered assistant that helps users understand their health conditions by analyzing symptoms provided in natural language.  
It uses a **Retrieval-Augmented Generation (RAG)** approach with **IBM Granite LLM** deployed on **IBM Cloud Lite services** to ensure trustworthy, multilingual, and safe healthcare guidance.  

 Disclaimer: This project **does not provide medical diagnosis**. It is designed for **educational and referral purposes only**. Always consult a certified doctor for medical advice.  

---

## Problem Statement  
People often rely on random internet searches to interpret their symptoms, which increases the risk of **misinformation** and **self-diagnosis mistakes**.  

Solution:  
- Lets users enter symptoms in natural language (e.g., *“I have sore throat and fever”*)  
- Retrieves data from **WHO guidelines, government health portals, and medical journals**  
- Provides:  
  - ✅ Probable causes  
  - ✅ Urgency level (low, medium, emergency)  
  - ✅ Home remedies & preventive care  
  - ✅ Guidance on when to consult a doctor   

---

## System Architecture  

### Workflow
1. **User Input** → Symptoms entered in chat-like interface  
2. **Granite Model (LLM)** → Understands symptoms & language  
3. **RAG Retrieval** → Fetches relevant medical data from WHO, Govt portals  
4. **Symptom Analysis Engine** → Maps to probable conditions, urgency level  
5. **Response Generation** → Provides clear, multilingual, safe advice  

### Diagram (Conceptual)
User Query → Granite LLM → RAG Retrieval → Symptom Analysis → Output

---

## End Users  
- General public (anyone with health concerns)  
- Rural & urban communities with limited access to doctors  
- Government health helplines & NGOs  
- Hospitals & clinics for pre-screening support  
- Educational institutions for awareness  

---

## Results  
- Deployed successfully on IBM Cloud  
- Demonstrated **symptom analysis + RAG retrieval** from trusted sources  
- Achieved **multilingual interaction** for wider accessibility  
- Enhanced **user trust** with safe health recommendations  

---

### Author’s Note

This project was developed as part of the IBM Hackathon to demonstrate the potential of Agentic AI with RAG in the healthcare domain.
It is not a medical diagnostic tool, but rather an educational and referral-based AI assistant built using IBM Granite & Watsonx.ai.
The goal is to reduce misinformation, promote preventive healthcare, and empower users with trusted medical guidance.

### Collaboration Note

We welcome collaborations, feedback, and contributions to improve this project!
Researchers can help by adding new trusted health data sources.
Developers can contribute by improving the RAG pipeline or building a front-end interface.
Students & open-source contributors can extend the project for awareness campaigns, NGOs, and rural health initiatives.
If you’d like to collaborate, feel free to:
- Star this repository
- Fork it & raise pull requests
- Open issues for suggestions or improvements

