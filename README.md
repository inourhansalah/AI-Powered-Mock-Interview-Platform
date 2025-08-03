# ReadySetHire 
**AI-Powered-Mock-Interview-Platform**
– Developed an AI-based chatbot to simulate job interviews via text and voice, evaluate technical answers, analyze soft skills, and deliver real-time feedback to enhance interview readiness. 
– Built using Large Language Models (LLMs) and a Retrieval-Augmented Generation (RAG) architecture to enhance question generation and contextual responses
 
---

##  Overview  
ReadySetHire simulates complete technical and behavioral interviews for computer science job seekers, featuring:  
- **Full interview simulations** (coding + soft skills)  
- **Instant AI feedback** with performance analytics  
- **Voice-based practice** in multiple languages  
- **Offline-capable** evaluation via local LLMs  

Developed at Cairo University's Faculty of Computers and Artificial Intelligence.  

---

##  Key Features  

###  **Soft Skills Module**  
- Voice-based behavioral questions  
- Evaluated by **Gemini API** on:  
  - Communication clarity  
  - Answer structure  
  - Professional impression  

###  **Coding Module**  
- 18,500+ Python problems  
- **Mistral 7B** evaluates:  
  - Code correctness  
  - Efficiency (Big-O)  
  - Best practices  

###  **Conceptual Module**  
- Theory questions (OOP/ML/Statistics)  
- Scores based on:  
  - Accuracy vs. ground truth  
  - Explanation clarity  
  - Concept coverage  

###  **Analytics Dashboard**  
- Skill radar charts  
- Progress timelines  
- Strength/weakness breakdowns  

---

##  Technical Architecture  

###  **Core Components**  
1. **Frontend**: Streamlit with custom CSS  
2. **AI Services**:  
   - Gemini (Google Cloud) for soft skills  
   - Mistral 7B (via vLLM) for tech evaluation  
   - Whisper (OpenAI) for speech-to-text  
3. **Database**: SQLite for session history  

###  **Workflow**  
1. User selects interview type  
2. System delivers randomized questions  
3. AI evaluates responses in <10s  
4. Feedback stored for progress tracking  

---

##  Unique Advantages  

| Feature | Benefit |  
|---------|---------|  
| **All-in-one prep** | Covers both technical + behavioral |  
| **Standardized grading** | Rubric-based scoring (1-5 scale) |  
| **Privacy-focused** | Local LLM processing option |  

---

##  Future Roadmap  
- Job-specific interview paths  
- Resume-driven question customization  
- Confidence scoring for soft skills  
- Multiplayer mock interview mode  

---


*Faculty of Computers and AI, Cairo University*  

---

