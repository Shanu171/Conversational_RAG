# Conversational RAG with PDF & Chat History 📄🤖  

This project is a **Conversational Retrieval-Augmented Generation (RAG) system** that enables users to **upload PDFs and chat with their content**, powered by the **DeepSeek-R1** model via the **Groq API**. The system also **maintains chat history** for a seamless user experience.  

## 🚀 Features  
✅ **DeepSeek-R1 & Gemma2-9B-IT** model selection  
✅ **Groq API-powered** for fast & efficient inference  
✅ **PDF upload support** for document-based Q&A  
✅ **Context-aware chat responses** with memory  
✅ **Streamlit-based UI** for an easy-to-use interface  

## 🛠️ Installation  

1. **Clone the repository**
   git clone https://github.com/Shanu171/Conversational_RAG.git
   cd Conversational_RAG

3. Create a virtual environment & install dependencies
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install -r requirements.txt

4. Set up environment variables
   Create a .env file and add your API keys:
   HF_TOKEN=your_huggingface_token

5. Run the Streamlit app
   streamlit run app.py

🎯 How It Works
Enter your Groq API key in the Streamlit sidebar.
Select a model (DeepSeek-R1 or Gemma2-9B-IT).
Upload one or multiple PDFs to extract knowledge.
Ask questions and receive context-aware responses!
Chat history is maintained to provide better contextual understanding.
🔗 Tech Stack
Streamlit - Frontend for interactive chat
Groq API - LLM inference
DeepSeek-R1 - Advanced large language model
LangChain - RAG and conversational memory
ChromaDB - Vector database for document retrieval
Hugging Face Embeddings - Text embedding models
📌 Future Enhancements
✅ Support for more LLM models
✅ Improved document retrieval efficiency
✅ Multi-user session management
