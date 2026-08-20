HR on Autopilot: An AI-Powered HR Policy Chatbot
📌 Project Overview

HR on Autopilot is an AI-powered HR Policy Chatbot designed to help employees quickly find information from an HR policy handbook.

The chatbot uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from the HR policy knowledge base and provide responses grounded in the available policy document.

🎯 Problem Statement

Employees often spend significant time searching through lengthy HR policy documents to find specific information.

Generic AI tools may also provide inaccurate or unsupported answers when responding to policy-related questions.

This project addresses the problem by providing an AI chatbot that retrieves information from a designated HR policy knowledge base before generating a response.

💡 Proposed Solution

The HR Policy Chatbot allows users to ask HR-related questions in natural language.

The system:

Receives the user's question.
Searches the HR policy knowledge base for relevant information.
Retrieves the appropriate policy context.
Uses an LLM to generate a response based on the retrieved information.
Provides the response to the user.
⚙️ Technologies Used
1. Dify
2. Retrieval-Augmented Generation (RAG)
3. Large Language Model (LLM)
4. HR Policy Handbook
5. GPT OSS 20B
   
🔄 How It Works
User Question
↓
HR Policy Chatbot
↓
Knowledge Base Retrieval
↓
Relevant Policy Information
↓
LLM Processing
↓
Grounded Response

🧠 Methodology

The project uses a RAG-based approach.

Instead of relying solely on the language model's general knowledge, the chatbot retrieves relevant information from the HR policy knowledge base and uses that information to generate its response.

This helps keep responses aligned with the available HR policy documentation.

🧪 Example Use Cases
In-Scope Question

Example:
"What is the maternity leave policy?"

The chatbot searches the HR policy knowledge base and provides information based on the available policy documentation.

Out-of-Scope Question

Example:
"Who won the FIFA World Cup?"

This question is unrelated to the HR policy knowledge base and should not be answered as an HR policy question.

🚀 Project Platform

The chatbot was developed and deployed using Dify.

Live Demo:
https://udify.app/chat/Cy3T3G4MDHNjCtFK

📂 Repository Contents

This repository contains documentation and supporting materials for the HR on Autopilot project.

Additional project files, screenshots, documentation, and presentation materials may be added as the project repository is developed.

👥 Project

Project: HR on Autopilot: An AI-Powered HR Policy Chatbot

Project Type: Generative AI / RAG Project

Platform: Dify

📌 Future Improvements

Potential future improvements include:

Expanding the HR knowledge base.
Improving retrieval accuracy.
Adding more HR policy categories.
Improving handling of ambiguous questions.
Adding additional evaluation and testing methods.
