# 🌐 AI Browser Agent with Gemini 2.0  

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![LangChain](https://img.shields.io/badge/Powered%20By-LangChain-green)
![Gemini](https://img.shields.io/badge/LLM-Gemini%202.0-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

An **AI-powered browser automation project** that uses **Gemini 2.0** with LangChain and the `browser_use` package.  
This demo shows how an AI agent can autonomously open a file, navigate the web, extract data, and generate summaries.

## 🚀 Features
- 🤖 **LLM-Powered Automation** – Uses **Gemini 2.0** to interpret natural language instructions.  
- 🌍 **Browser Integration** – Launches a Chrome session for real-world interactions.  
- 🔍 **Information Retrieval** – Finds StackOverflow users and extracts their **reputation score**.  
- 📊 **Summarization** – Returns a concise summary of the topics the user contributes to.  
- ⚡ **Async Execution** – Runs tasks asynchronously with Python `asyncio`.  

## ⚙️ Installation & Setup  

### 1. Clone the Repository  
git clone https://github.com/Nv1023/ai-browser-gemini.git
cd ai-browser-gemini

2. Create a Virtual Environment
Copy code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install Dependencies
Copy code
pip install -r requirements.txt

4. Set Environment Variable
Get your Gemini API key from Google AI Studio.
Copy code
export GEMINI_API_KEY=your_api_key_here   # macOS/Linux
set GEMINI_API_KEY=your_api_key_here      # Windows (PowerShell)

5. Run the Project
Copy code
python main.py

## 📂 Project Structure
Copy code
ai-browser-gemini/
│── main.py               # Main demo script
│── requirements.txt       # Dependencies
│── README.md              # Documentation

## 🧑‍💻 Example Task
The agent is configured to:

Open a local file users.txt

Search for user835611 on StackOverflow

Accept all cookies

Fetch their reputation score

Summarize the topics they contribute to

Sample Output:

yaml
Copy code
User: user835611  
Reputation: 14,520  
Main Topics: Python, Flask, SQLAlchemy, REST APIs  

---

## 🔮 Future Enhancements
Add support for multi-user lookup

Export results as JSON/CSV reports

Extend to multiple platforms (Reddit, GitHub, Twitter)

Integrate voice-based instructions

---

## 📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

---

## 👨‍💻 Author
**Naveen j**
📧 Email: naveenjeyakala333@gmail.com
🔗 GitHub: jknaveen00
