# Deploy-LLM-Chatbot-Gradio-Groq-Streamlit-Python
Can Groq's Llama models power intelligent conversational AI? This project demonstrates LangChain + Gradio with Groq's Llama 3.1 through a real-time AI Chatbot featuring conversation memory and dynamic responses. Live Demo: https://deploy-llm-chatbot-gradio-groq.streamlit.app/ 🤖✨

🔍 Project Overview:

LLM-Powered Conversations: llama-3.1-8b-instant via Groq API for fast, context-aware dialogue
<br>
Real-time Gradio UI: Gradio chat interface with copy button, responsive design
<br>
LangChain Memory: LangChain manages HumanMessage/SystemMessage history for coherent conversations
<br>
Session Persistence: Full chat history retained across interactions
<br>
Production Deployed: Live at https://deploy-llm-chatbot-gradio-groq.streamlit.app/
<br>
Error-Resilient: Graceful API key/environment handling

🎯 Learning Outcomes:

LangChain: Orchestration framework for chaining LLM calls, managing prompts, and conversation memory
<br>
Gradio: Python library to instantly create/share beautiful ML demos (chat UIs, 2 lines of code)
<br>
Integrating Groq's high-speed Llama models with Python web frameworks
<br>
Building stateful conversational AI with production-grade UIs
<br>
Deploying Gradio apps via Streamlit Cloud

⚙️ Technologies:
LangChain (chat history) | Gradio (web UI) | Groq API (Llama 3.1) | Python | python-dotenv

Local Setup: python main.py → http://127.0.0.1:7860
Dependencies: pip install gradio langchain-groq langchain-core python-dotenv
.env: GROQ_API_KEY=your_key_from_console.groq.com
