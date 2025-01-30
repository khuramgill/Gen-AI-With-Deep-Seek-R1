# 🧠 DeepSeek Code Companion  

🚀 **Your AI Pair Programmer with Debugging Superpowers**  

This is a **powerful AI coding assistant** built with **DeepSeek, Ollama, and LangChain**. It helps with debugging, code documentation, and designing efficient solutions.  

## ✨ Features  
- 🐍 **Python Expert** – Assists with writing and optimizing Python code  
- 🐞 **Debugging Assistant** – Provides strategic print statements for debugging  
- 📝 **Code Documentation** – Generates clear and concise documentation  
- 💡 **Solution Design** – Helps with structuring efficient and scalable solutions  

---

## 🔧 Setup & Installation  

### 1️⃣ Install Dependencies  
Ensure you have **Streamlit, Ollama, and LangChain** installed:  

```bash
pip install streamlit langchain_ollama
```

You also need to install **Ollama** and **DeepSeek models** on your local machine. If you haven't already:  

- Download and install **Ollama** from [Ollama.ai](https://ollama.ai/)  
- Pull the **DeepSeek models** (example for `deepseek-r1:1.5b`):  

```bash
ollama pull deepseek-r1:1.5b
```

### 2️⃣ Run the Chatbot  

```bash
streamlit run chatbot.py
```

This will launch the **DeepSeek Code Companion** in your browser.  

---

## 🛠️ How It Works  

1. **Select a Model** – Choose between `deepseek-r1:1.5b` or `deepseek-r1:3b` in the sidebar.  
2. **Ask Questions** – Type your coding queries in the chat input.  
3. **Get AI-Powered Assistance** – Receive accurate and optimized solutions with debugging hints.  

---

## 🎨 UI & Theming  

The chatbot features a **dark-themed** UI with:  
- Styled **text inputs, dropdowns, and chat messages**  
- **Custom CSS** for a modern developer-friendly look  

---

## 📜 Technologies Used  

- **[Streamlit](https://streamlit.io/)** – For the interactive UI  
- **[Ollama](https://ollama.ai/)** – To run AI models locally  
- **[LangChain](https://python.langchain.com/)** – For AI chat processing  
- **DeepSeek Models** – Powerful AI models for coding assistance  

---

## 🛠️ Future Enhancements  

✅ Support for **more programming languages**  
✅ **Advanced debugging tools**  
✅ **Improved contextual understanding** for better responses  

---

## 📜 License  

This project is **open-source**. Feel free to use, modify, and contribute!  

---

🔥 *Built with DeepSeek, Ollama, and LangChain – Your AI-powered coding assistant!* 🚀
