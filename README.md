# HR on Autopilot 🚀
**An AI-Powered HR Company Policy Chatbot**

Employees waste hours hunting through long HR policy documents. Generic AI tools often hallucinate or give outdated answers.  

**HR on Autopilot** solves this with a Retrieval-Augmented Generation (RAG) chatbot that answers only from the official HR policy handbook — accurate, grounded, and instant.

### 🎯 Problem
- Staff spend too much time searching policy PDFs
- ChatGPT-style tools invent answers that aren’t in the handbook
- HR teams get flooded with repetitive questions

### 💡 Solution
A Dify-powered chatbot that:
1. Takes a natural language question
2. Retrieves the relevant sections from the HR policy knowledge base
3. Generates a clear, grounded answer using an LLM
4. Refuses questions that fall outside the policy documents

---

### ⚙️ Tech Stack
- **Platform**: Dify
- **Architecture**: Retrieval-Augmented Generation (RAG)
- **LLM**: Llama 3.1 8b instant updated to GPT-OSS-20b
- **Knowledge Base**: HR Policy Handbook (PDF)
- **Deployment**: Dify Cloud (Udify)

### 🔄 How It Works
User Question
↓
Knowledge Retrieval (from HR Policy PDF)
↓
Relevant Policy Chunks
↓
LLM (grounded generation)
↓
Accurate, Policy-Based Answer

---

### Architecture
[User] → [Dify Chatflow]
├── Knowledge Retrieval Node (Bridge Policy.pdf)
├── LLM Node - (Llama 3.1 8b instant) updated to GPT-OSS-20b
└── Response
---

### 💬 Example Interactions

**In-Scope**  
**User**: What is the maternity leave policy?  
**Bot**: According to the HR Policy Handbook, eligible employees are entitled to [16] weeks of maternity leave... (grounded answer)

**Out-of-Scope**  
**User**: Who is the president of Nigeria?  
**Bot**: I couldn't answer that question. I answer based on the company’s HR policy documents only.

---

### Live Demo
👉🏾try it here (https://udify.app/chat/Cy3T3G4MDHNjCtFK)

---

### 📂 Repository Contents
- `README.md` – Project documentation
- `HR_on_Autopilot_3MTT_Presentation.pptx` – Project presentation
- Screenshots of the live chatbot

---

### Future Improvements
- Expand knowledge base with more policy documents
- Add metadata filtering by policy category
- Implement user feedback loop (thumbs up/down)
- Improve handling of multi-hop and ambiguous questions
- Add automated evaluation pipeline

---

### Project Info
**Project Name**: HR on Autopilot – AI-Powered HR Company Policy Chatbot  
**Type**: Generative AI / RAG Application  
**Platform**: Dify  
**Status**: Live Demo Available

### How I Built It
1. Created a new Chatflow in Dify
2. Uploaded the HR Policy PDF into the Knowledge base
3. Configured the Knowledge Retrieval node to use the policy document
4. Connected it to an LLM node (Llama 3.1 8b instant) updated to GPT-OSS-20b 
5. Added strict system instructions to stay grounded in the retrieved context and refuse out-of-scope questions
6. Tested with a mix of in-scope and out-of-scope questions
7. Published the app

 **MODEL UPDATE**
The project was initially developed and demonstrated using Llama 3.1 8B Instant. Following the decommissioning of this model, the deployed chatbot was updated to GPT OSS 20B. The project’s core functionality, RAG architecture, knowledge base, and HR policy focus remain unchanged.

### Team
- Ochu Mariam (lead)
- Verse Vitalis
- Obidah Abalis
- Aminu Saminu
  
Deeptech Capstone project supervised by Mentor Eldad Akhaumere 
