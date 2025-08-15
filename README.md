# Task 4: General Health Query Chatbot (Prompt Engineering Based)

## 📌 Objective
The objective of this task is to create a chatbot that can answer **general health-related questions** using a Large Language Model (LLM).  
The chatbot should:
- Provide clear, friendly, and helpful responses.
- Use prompt engineering to control tone and content.
- Include safety measures to avoid giving harmful, diagnostic, or prescription-specific advice.

---

## 📊 Dataset
- **Dataset Used**: No pre-collected dataset required.  
  The chatbot relies on a live LLM API (e.g., OpenAI GPT-3.5) or an open-source model (e.g., Mistral-7B-Instruct) to generate responses.  
- **Knowledge Source**: The model’s pre-trained knowledge and carefully engineered prompts.

---

## 🤖 Models Applied
- **Primary Model**:  
  - Option 1: OpenAI GPT-3.5 API  
  - Option 2: Hugging Face hosted Mistral-7B-Instruct model  
- **Prompt Engineering**:
  - Example system prompt:  
    `"You are a friendly and helpful medical assistant. Provide safe, clear, and non-diagnostic health information to users."`

---

## 📈 Key Results & Findings
- The chatbot successfully:
  - Responded to common health questions in an easy-to-understand tone.
  - Avoided making diagnoses or giving direct prescriptions.
  - Adapted its responses based on user prompts due to effective prompt engineering.
- Safety filters and disclaimers reduced the risk of harmful guidance.

---

## 🚀 Future Improvements
- Add retrieval from verified medical resources for more up-to-date answers.
- Implement intent detection to redirect emergency queries to professional help.
- Integrate speech-to-text for voice-based health queries.
