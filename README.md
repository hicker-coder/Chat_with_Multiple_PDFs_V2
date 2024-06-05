# Chat with Your PDFs

Chat with Your PDFs is a Streamlit-based web application that allows users to upload PDF documents, process their text, and interact with the content using an AI chatbot. The application utilizes FAISS for efficient similarity search, OpenAI embeddings for semantic understanding, and Streamlit for the front-end interface.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Contact](#contact)

## Features
- Upload multiple PDF documents for processing
- Extract text from PDF files
- Split extracted text into manageable chunks
- Create a vector store for efficient text similarity search using FAISS
- Integrate with OpenAI for text embeddings
- Chatbot interface to interact with the uploaded PDFs
- Sidebar for uploading PDFs and accessing help

## Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/hicker-coder/Chat_with_Multiple_PDFs_V2.git
    cd Chat_with_Multiple_PDFs_V2
    ```

2. **Create and activate a virtual environment (optional but recommended)**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables**
    Create a `.env` file in the root directory and add your configuration details. For example:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

## Usage

1. **Run the Streamlit application**
    ```sh
    streamlit run main.py
    ```

2. **Open your browser and navigate to**
    ```
    http://localhost:8501
    ```

3. **Upload PDFs**
    - Use the sidebar to upload one or multiple PDF documents.
    - Click the "Process" button to extract and process the text.

4. **Interact with the chatbot**
    - Enter your questions in the text input field and interact with the content of your uploaded PDFs.


## Dependencies

- `langchain==0.0.184`
- `PyPDF2==3.0.1`
- `python-dotenv==1.0.0`
- `streamlit==1.18.1`
- `openai==0.27.6`
- `faiss-cpu==1.7.4`

To use Huggingface LLMs, uncomment the following dependencies in `requirements.txt`:
- `huggingface-hub==0.14.1`
- `InstructorEmbedding==1.0.1`
- `sentence-transformers==2.2.2`


## Contact

If you need any help, please refer to the FAQ section or contact us at amin.mba@iuj.ac.jp.

