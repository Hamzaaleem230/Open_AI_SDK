# 🧠 OpenAI SDK – Gemini Agent Integration (Colab)

This project demonstrates how to integrate Google's Gemini model with the `openai-agents` library using Google Colab.

## 🚀 Getting Started

Follow these steps to set up and run the agent in your Colab notebook.

### 1. 📁 Clone this repository (optional)

You can either clone it locally or open the notebook directly in Google Colab.

```bash
git clone https://github.com/Hamzaaleem230/Open_AI_SDK.git
```

---

### 2. 📓 Open the Notebook
Open openaisdk.ipynb in Google Colab.

---

### 3. 🔐 Set up your API key
*) Go to: AI Studio API Key
*) Generate a new API key.
*) In Colab, go to Runtime > Secrets and add a new secret:
    *) Name: GOOGLE_API_KEY
    *) Value: your generated API key
    
Make sure the key is enabled in the notebook's secrets.

---

### 4. 🛠️ Install Dependencies
The notebook already includes this:
```python
    pip install -Uq openai-agents
```

---

### 5. ✅ Code Overview
*) Uses openai-agents for running a conversational AI agent.
*) Gemini 2.0 Flash model is configured via OpenAIChatCompletionsModel.
*) userdata.get("GOOGLE_API_KEY") ensures the API key stays secure.
*) Runner.run_sync is used to execute the agent prompt.

---

### 6. 💡 Example Output
CALLING AGENT

I'm doing well, thank you! How can I assist you today?

---

### 📌 Requirements
*) Python 3.x (auto-handled in Colab)
*) A valid Gemini API key
*) Google Colab (recommended)

---

### 📬 Contact
For help, feel free to open an issue or connect via GitHub.

---

© 2025 by Hamza Aleem. Built with 💙 using Gemini + Colab + openai-agents.
