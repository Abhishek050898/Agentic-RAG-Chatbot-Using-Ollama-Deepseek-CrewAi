# Agentic RAG Chatbot – PDF & Web Search with Ollama

📌 Agent-based RAG system for document-based Q&A and real-time web search.

🔍 Uses CrewAI, Qdrant, Streamlit, Ollama for semantic search & AI-powered responses.

## How to Use
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/agentic-rag-chatbot.git
cd agentic-rag-chatbot
```

### 2️⃣ Install & Run Ollama
```sh
curl -fsSL https://ollama.com/install.sh | sh  # For Mac/Linux
winget install Ollama  # For Windows

# Start Ollama
ollama serve

# Download Llama3
ollama pull llama3

# Check if the model is installed using:
ollama list
```

### 4️⃣ Run the Application
```sh
streamlit run app.py
```

