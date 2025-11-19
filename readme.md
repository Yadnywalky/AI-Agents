
# AI Agents using Google ADK

## 📌 Project Overview
This project demonstrates how to build **AI Agents** using **Google ADK (AI Development Kit)**.  
It showcases how agents interpret instructions, generate responses, and process actions with intelligent workflows.

The notebook includes:
- Initializing AI Agents  
- Using Google ADK models  
- Helper utilities  
- Prompt and response handling  
- Structured output generation  

---

## 🚀 Features
- Single-agent intelligent workflow  
- Modular and clean architecture  
- Real-time response streaming  
- Easy to extend and customize  

---

## 🛠️ Technologies Used
- Python  
- Google ADK  
- Generative AI Models  
- Jupyter Notebook  

---

## 📂 Project Structure
```
AI Agents.ipynb         # Main notebook implementing the AI agent
readme.md               # Documentation (this file)
```

---

## ⚙️ Setup Instructions

### 1. Install Dependencies
```bash
pip install google-generativeai google-adk kaggle-secrets
```

### 2. Configure the API Key

#### If running on Kaggle:
- Go to *Settings → Secrets*
- Add a secret named: `GOOGLE_API_KEY`

#### If running locally:
```bash
export GOOGLE_API_KEY="your_api_key_here"
```

---

## 💡 How It Works
1. Import ADK agent and model components  
2. Initialize an AI agent  
3. Provide input prompts to the agent  
4. The agent processes the request and returns answers using Google models  

---

## 🧪 Example Usage
```python
response = agent.run("Explain supervised learning in simple words.")
print(response)
```

---

## 📈 Future Enhancements
- Multi-agent collaboration  
- User interface integration  
- Persistent agent memory  
- Voice-enabled agent  
- Domain-specific custom agents  

---

## 📜 License
This project follows the licensing terms included inside the notebook.

---

## 🤝 Contributing
Issues, suggestions, and contributions are always welcome!
