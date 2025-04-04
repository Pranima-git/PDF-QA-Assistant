# PDF-QA-Assistant
Smart assistant that answers questions from PDF using LangChain, HuggingFace, Chroma, and Groq LLaMA3.
🚀 Technologies Used

- **LangChain** – For creating the question-answering pipeline
- **HuggingFace Embeddings** – To convert text into vectors
- **Chroma Vector DB** – To store and retrieve document chunks
- **Groq’s LLaMA3 Model** – For generating intelligent responses

📌 Use Cases

- Students asking questions about lecture notes.
- Legal teams analyzing long case files.
- Customer support searching product manuals.

💡 How It Works

1. Upload a PDF.
2. The PDF is split into smaller chunks.
3. Each chunk is embedded and stored in a vector database.
4. You ask a question.
5. The system finds relevant chunks and sends them to LLaMA3 for a smart answer.
