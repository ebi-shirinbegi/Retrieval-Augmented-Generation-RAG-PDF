# Retrieval-Augmented Generation (RAG) System Using LLMs

This project implements a Retrieval-Augmented Generation (RAG) system that integrates both OpenAI's GPT and Llama3.1 models. It enables efficient document retrieval and question answering by combining the power of large language models with context-based responses.

## Features

- Support for both OpenAI GPT and Llama3.1 models
- PDF document loading and processing
- Custom question-answering prompt template
- Document vectorization and retrieval using Hugging Face embeddings
- Streaming responses for real-time interaction

## Requirements

- Python 3.x
- Ollama (Install Ollama on your machine and download Llama model)
- OpenAI API key (for GPT models)
- Llama3.1 (if not using GPT)
- Various Python libraries (see `requirements.txt`)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/ebi-shirinbegi/rag-pdf.git
    cd rag-pdf
    ```

2. Create a virtual environment and install the required packages:

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

## Usage

The project is structured as a Jupyter notebook (`asset.ipynb`). To use it:

1. Start Jupyter Notebook (Using VS Code is recommended).
2. Open `asset.ipynb`.
3. Run the cells sequentially to:

    - Initialize the chosen model and embeddings.
    - Load and process the PDF document.
    - Set up the question-answering pipeline.
    - Perform document retrieval and answer questions.

## Key Components

- **Model Initialization:** Choose between GPT and Llama3.1.
- **PDF Processing:** Load and split PDF documents.
- **Custom Prompt:** Define a template for question-answering.
- **Document Vectorization:** Create a searchable vector store.
- **Retrieval Pipeline:** Combine document retrieval with the Q&A system.
- **Streaming Responses:** Get real-time outputs for longer queries.

## Customization

- Replace `afghanistan.pdf` with your own PDF document.
- Adjust the model selection in the notebook (GPT vs. Llama3.1).
- Modify the prompt template for different use cases.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/ebi-shirinbegi/rag-pdf/issues) if you want to contribute.

## Author

**Ebrahim Sharifi**
