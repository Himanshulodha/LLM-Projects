# 🕵️‍♂️ Intelligent Agent Hub
### repository contains a Streamlit application that integrates various AI-powered tools to assist with coding, mathematical calculations, real-time information retrieval, and research. It leverages the capabilities of LangChain agents, Groq's LLM (Large Language Model), and several APIs to provide a versatile and dynamic querying environment.

## 🌟 Features
## Agent 1:
### Tools: Python REPL, Shell commands.
### Use Case: Ideal for performing mathematical calculations, running Python code, and executing shell commands.
## Agent 2:
### Tools: DuckDuckGo, Google Search, YouTube Search.
### Use Case: Suitable for retrieving real-time information from the web, including searching for videos on YouTube.
## Agent 3:
### Tools: DuckDuckGo, Wikipedia, ArXiv, PubMed, Google Search.
### Use Case: Perfect for research purposes, providing access to scientific literature and encyclopedic knowledge.
## Manager Agent:
### Manages the three agents above to provide a comprehensive response depending on the query type.
## 🛠️ Setup Instructions
### 1. Clone the Repository
### git clone https://github.com/yourusername/intelligent-agent-hub.git
### cd intelligent-agent-hub

### 2. Create a Virtual Environment
### python3 -m venv venv
### source venv/bin/activate

## 3. Install Dependencies
### pip install -r requirements.txt
### Set Up Environment Variables

## 4. Create a .env file in the root directory and add your API keys:
### GROQ_API_KEY=your_groq_api_key
### SERP_API_KEY=your_serp_api_key

## 5. Run the Streamlit App
## streamlit run app.py

## 🔧 Usage
### 1.Open the application in your browser after running the Streamlit command.
### 2.Enter your query in the input box.
### 3.Click "Get Answer" to see the response generated by the appropriate agent.

## 🙌 Acknowledgments
### LangChain for the powerful AI framework.
### Streamlit for the interactive web application interface.
