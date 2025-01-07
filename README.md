# Sutra-AI
Assignment for  AI Engineer Intern
---

# Chat with PDF Application 😻  

**Chat with PDF** is a user-friendly Streamlit app that enables interactive Q&A with uploaded PDF documents. The app extracts text, generates embeddings, and provides accurate answers to your queries using OpenAI's GPT-4.  

---

## 🌟 Features  

- **PDF Upload**: Upload one or multiple PDF files for analysis.  
- **Text Extraction & Chunking**: Automatically extracts and divides PDF content into manageable chunks.  
- **Embedding Generation**: Uses OpenAI's `text-embedding-ada-002` model to convert text into embeddings.  
- **Question Answering**: Ask questions about the content and receive detailed, context-aware responses via GPT-4.  
- **Contextual Insights**: Displays relevant text excerpts supporting the generated answers.  
- **Cross-Document Querying**: Supports searching across multiple uploaded PDFs.  

---

## 🛠️ Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo/chat-with-pdf.git  
   cd chat-with-pdf  
   ```  

2. Set up a virtual environment:  
   ```bash  
   python3 -m venv venv  
   source venv/bin/activate  # For Linux/MacOS  
   .\venv\Scripts\activate   # For Windows  
   ```  

3. Install required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Add your OpenAI API key:  
   - Create a `.env` file in the root directory.  
   - Add the following line to the file:  
     ```  
     OPENAI_API_KEY=your_openai_api_key_here  
     ```  

---

## 🚀 Usage  

1. Start the application:  
   ```bash  
   streamlit run app.py  
   ```  

2. Interact with the app:  
   - Upload one or more PDF files.  
   - Wait for text processing and embedding generation.  
   - Enter your question, and the app will provide an answer along with relevant context from the uploaded documents.  

---

## 📝 Notes  

- **Highlights on PDFs**: The app displays context excerpts but does not yet support direct text highlighting in PDFs.  
- **API Limitations**: Ensure your OpenAI API key has sufficient usage limits for processing and querying.  
- **Cross-Document Insights**: Queries are processed across all uploaded documents, making multi-document analysis seamless.  

---

Feel free to contribute or suggest improvements! 😊
