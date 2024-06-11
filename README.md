# RAG Chatbot

This project aims to create a Retrieval-Augmented Generation (RAG) chatbot. This chatbot will leverage Large Language Models (LLMs) to interact with users based on retrieved documents.

## Prerequisites

- Python 3.6+
- An API key for an LLM provider (OpenAI, AzureOpenAI, HuggingFace, etc.)

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
   ```
   
2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   ```

3. **Activate the virtual environment**
  On Windows:

  ```bash
  .\venv\Scripts\activate
  ```
On macOS/Linux:

  ```bash
source venv/bin/activate
```

4. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Configuration
Set up your API keys:

Ensure you have your API keys ready for the LLM provider you are using (OpenAI, AzureOpenAI, HuggingFace, etc.).

Configure the document loader:

Update the file path of the document in the document loader. This can be done in the script where you set up your document loader.


