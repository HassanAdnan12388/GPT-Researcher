# GPT-Researcher
# **Integrating Mistral-7B with GPT-Researcher Using Fireworks**

## **Project Overview**
This project focuses on integrating the **Mistral-7B** open-source LLM into the **GPT-Researcher** codebase using the **Fireworks** platform. The implementation is done using **Cursor**, an AI-first code editor that enhances development workflows through **retrieval-augmented generation (RAG)**.

---

## **Summary**
### **Tasks Covered**
1. **Setup and Environment Configuration**
   - Install and configure **Cursor**.
   - Clone the **GPT-Researcher** repository.
   - Create and activate a **virtual environment**.

2. **Fireworks LLM Provider Implementation**
   - Developed `FireworksProvider` class for LLM integration.
   - Utilized **LangChain Fireworks API** for chat model interaction.
   - Implemented **asynchronous streaming** for real-time responses.

3. **Enhancements in GPT-Researcher**
   - Integrated the **Fireworks LLM provider** into the research pipeline.
   - Enabled **environment variable-based API authentication**.
   - Implemented **message conversion system** to support structured inputs.

4. **Testing and Deployment**
   - Ran the GPT-Researcher with **Mistral-7B**.
   - Verified response generation via GUI and backend logs.
   - Debugged errors using **Cursor's AI assistance**.

---

## **Technologies Used**
- **Python**: Core language for implementation.
- **LangChain Fireworks**: LLM integration framework.
- **OpenAI GPT-Researcher**: Autonomous research agent.
- **Cursor AI Editor**: AI-assisted development.
- **FastAPI & Uvicorn**: Backend server framework.

---

## **Architecture**
1. **Environment Setup**
   - Install dependencies (`pip install -r requirements.txt`).
   - Set up API keys and authentication.

2. **Fireworks LLM Integration**
   - Implement `FireworksProvider` for API-based model access.
   - Handle message conversion (`SystemMessage`, `HumanMessage`).
   - Support synchronous and **asynchronous streaming**.

3. **GPT-Researcher Integration**
   - Modify backend utilities to include Fireworks API.
   - Test research queries through **Mistral-7B**.

4. **Testing & Deployment**
   - Launch the server: `uvicorn main:app --reload`.
   - Run test queries via `http://localhost:8000` GUI.

---

## **Key Features**
- **Seamless integration** of Mistral-7B into GPT-Researcher.
- **Asynchronous streaming** for efficient chat response handling.
- **Modular FireworksProvider** for easy expansion.
- **Environment-based API authentication**.
- **AI-assisted code generation** using Cursor.



