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
   git clone https://github.com/your-username/tech-titans.git
   cd tech-titans
