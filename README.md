# README

## LLM and RAG 

This is a practice try-outs aimed at deepening understanding of Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG). The project leverages OpenAI APIs and contains two Jupyter notebooks that demonstrate basic LLM functionality and an introduction to RAG.

---

## Contents

1. **Notebooks**
   - `introduction_to_llms.ipynb`: A simple introductory notebook to explore OpenAI API capabilities. It includes basic examples such as translating text, serving as a "hello-world" for working with LLMs.
   - `basic_rag_pipeline.ipynb`: Demonstrates the foundational steps of RAG:
     - Loading mini/LLaMA articles.
     - Converting articles into chunks.
     - Embedding these chunks using OpenAI embeddings.
     - Performing basic inference to answer questions based on the embedded data.
   - `langchain_application.ipynb`: Explores LangChain's PromptTemplates and SummarizationChain for building prompt-based workflows and summarization tasks.
   - `news_article_summarizer_langchain.ipynb`: Implements a news article summarizer using LangChain's summarization capabilities.
   - `llama_index_overview.ipynb`: Provides an overview of LlamaIndex, utilizing the `WikipediaReader` for data ingestion and retrieval.

2. **Requirements**
   - Python 3.8+
   - OpenAI Python SDK
   - Jupyter Notebook

---

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/llm-rag-hobby-project.git
   cd llms-notebooks
   ```


2. Set up your OpenAI API key:
   - Obtain an API key from the [OpenAI Dashboard](https://platform.openai.com/).
   - Create a `.env` file and add your API key:
     ```env
     OPENAI_API_KEY=your_api_key_here
     ```

3. Explore the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

---

## Usage

### `introductions_to_llm.ipynb`
- This notebook demonstrates a basic translation example using OpenAI's API.
- Modify the prompt or language pairs to experiment further.

### `basic_rag_pipeline.ipynb`
- Step-by-step demonstration of RAG:
  1. Load LLaMA articles (or any other dataset).
  2. Split articles into manageable chunks.
  3. Embed the chunks using OpenAI's embedding API.
  4. Query the embedded data to retrieve relevant information.

---

## Next Steps

- Explore advanced RAG workflows.
- Experiment with other datasets and embeddings.
- Integrate additional LLMs for comparison (e.g., Hugging Face models).
- Build a simple application (e.g., chatbot or search interface).

---

## Contributing

This project is currently a personal hobby project, but contributions and suggestions are welcome!
