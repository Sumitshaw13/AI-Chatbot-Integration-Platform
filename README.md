# Tech-Titans - AI-Powered Q&A with PDF and Chat Integration

This project is a web application built with Streamlit that combines AI-powered question-answering capabilities from PDF documents and a conversational AI interface. It also integrates with Firebase to store and retrieve user question-answer histories.

## Features

- **PDF Upload & Processing:** Users can upload multiple PDF files, and the application extracts the text, processes it into chunks, and stores it in a vector store for similarity search.
- **Generative AI Q&A:** Users can ask questions based on the uploaded PDF, and the AI will provide answers using the stored content.
- **Chat with AI:** Users can interact with a conversational AI (Google Gemini) to ask questions and receive responses.
- **Question History:** Users can view their past questions and AI-generated answers stored in Firebase Realtime Database.
- **Save Chat History:** The chat history can be saved to a `.txt` file and downloaded.

## Installation

### Prerequisites

- Python 3.7 or later
- Required libraries (see `requirements.txt`)

### Steps to Install

1. Clone the repository:

   ```bash
   https://github.com/Jyotish2002/PdfQuestions
   cd PdfQuestions```
2.Install the required dependencies:


     pip install -r requirements.txt
3. Run the application:
   ```bash
   streamlit run app.py
### Usage
- **Upload PDFs:** Upload one or more PDF documents, and click "Submit & Process" to extract text from them.
- **Ask Questions:** Once the PDFs are processed, you can type in a question, and the AI will provide an answer based on the uploaded content.
- **Chat with AI:** You can also ask general questions to the AI, and it will provide responses.
- **View Question History:** You can check your past questions and answers stored in Firebase.
- **Download Chat History:** You can save and download the entire chat history in .txt format.

