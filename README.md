**Document Query Chatbot with Ollama Mistral**

**Overview**
This project showcases a chatbot built using the Ollama Mistral model. The chatbot can process documents from specified URLs and answer questions based on the content of those documents. The system uses Retrieval-Augmented Generation (RAG) to enhance the accuracy and relevance of the responses. The project is implemented in two Python files: app.py and ui.py.

**Files**
**app.py**
This script demonstrates the core functionality of the chatbot:

**Data Loading**: Loads documents from specified URLs.
**Text Splitting**: Splits documents into manageable chunks.
**Embedding Generation**: Converts document chunks into embeddings and stores them in a vector store.
**Before and After RAG**: Shows the chatbot's response without context (Before RAG) and with context (After RAG).

**ui.py**
This script provides a user interface using Gradio:

**User Input Processing**: Takes URLs and a question as input.
**Data Loading and Processing**: Loads documents, splits them, and stores embeddings similar to app.py.
**RAG Implementation**: Answers the question based on the context extracted from the documents.
**Gradio Interface**: Provides a simple web-based UI for users to interact with the chatbot.

**How to Run**
**Install Dependencies**:
pip install langchain_community gradio


**Run the App**:
**For the core functionality**:
python app.py

**For the user interface**:
python ui.py

**What I Learned**
**Language Models**: Gained hands-on experience with the Ollama Mistral model for natural language processing tasks.
**Data Processing**: Learned to handle and process large textual data by splitting documents into chunks and generating embeddings.
**Retrieval-Augmented Generation (RAG)**: Implemented RAG to improve the relevance of the chatbot's responses, demonstrating the importance of context in NLP applications.
**Web-based Interfaces**: Utilized Gradio to create a user-friendly interface, making it easier for users to interact with the chatbot.
