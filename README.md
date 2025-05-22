# Building-Agentic-RAG-with-Llamaindex

This repository contains Jupyter notebooks and completed assignments from the DeepLearning.AI course, "**Building Agentic RAG with LlamaIndex**." This specialized course focuses on the cutting-edge intersection of Retrieval Augmented Generation (RAG) and AI agents, demonstrating how to build sophisticated, intelligent systems that can dynamically interact with and reason over diverse knowledge bases.

## Skills Demonstrated & Key Learnings:

* **Advanced Retrieval Augmented Generation (RAG):** Moving beyond basic RAG to construct more intelligent and robust systems.
* **AI Agents & Tools:** Understanding and implementing AI agents that can utilize various tools to interact with data.
* **LlamaIndex Framework:** In-depth practical application of the LlamaIndex library for building complex RAG and agentic workflows.
* **Multi-document & Multi-modal Retrieval:** Strategies for handling and querying information across diverse document types and formats.
* **Router Query Engines:** Implementing intelligent routing mechanisms to direct queries to the most relevant data sources or specialized query engines.
* **Recursive Retrieval:** Designing systems that can perform iterative or nested information retrieval.
* **Query Transformation:** Techniques for optimizing and refining user queries for better retrieval results.
* **Structured vs. Unstructured Data Handling:** Integrating LLMs with both structured (e.g., SQL databases) and unstructured (e.g., text documents) information.
* **Data Agents:** Building agents specifically designed to interact with and extract insights from complex datasets.
* **Prompt Engineering & Context Management:** Crafting effective prompts for LLMs within complex, multi-step RAG pipelines.
* **Python Programming for LLM Applications:** Practical coding skills in Python for developing sophisticated AI solutions.

## Project Breakdown & Notebook Highlights:

Each directory corresponds to a lesson or module, containing the relevant Jupyter notebooks that walk through the concepts and practical implementations.

### 1. Introduction to Agentic RAG & Router Query Engine
[Link to Notebook: `lesson_1_router_query_engine.ipynb`](lesson_1_router_query_engine/lesson_1_router_query_engine.ipynb)
* **Objective:** Understand the core concept of agentic RAG and implement a basic router query engine to select between multiple document indices.
* **Key Concepts Applied:** `RouterQueryEngine`, `Selector` (LLM-based or Pydantic), `VectorStoreIndex`.
* **Results:** Successfully built a system that intelligently directs queries to the most appropriate knowledge source, a foundational step for advanced RAG.

### 2. Query Transformation & Recursive Retrieval
[Link to Notebook: `lesson_2_query_transformation_recursive_retrieval.ipynb`](lesson_2_query_transformation_recursive_retrieval/lesson_2_query_transformation_recursive_retrieval.ipynb)
* **Objective:** Explore techniques to modify queries for better retrieval and implement recursive retrieval for deeper information exploration.
* **Key Concepts Applied:** `MultiStepQueryEngine`, query rewriting, hierarchical document structures, parent-child relationships in indexing.
* **Results:** Developed more robust retrieval strategies by refining initial queries and enabling multi-level information lookup.

### 3. Data Agents & Structured Data Integration
[Link to Notebook: `lesson_3_data_agents_structured_data.ipynb`](lesson_3_data_agents_structured_data/lesson_3_data_agents_structured_data.ipynb)
* **Objective:** Learn to build agents that can interact with structured data sources (like SQL databases) and combine them with unstructured RAG.
* **Key Concepts Applied:** `SQLAgent`, `OpenAIFunctionsAgent`, connecting LLMs to external tools/APIs, structured data querying.
* **Results:** Implemented an agent capable of answering questions requiring data from both structured and unstructured sources, showcasing multi-modal information synthesis.

### 4. Advanced Tool Use & Function Calling
[Link to Notebook: `lesson_4_advanced_tool_use.ipynb`](lesson_4_advanced_tool_use/lesson_4_advanced_tool_use.ipynb)
* **Objective:** Deep dive into advanced tool usage and function calling mechanisms to extend agent capabilities.
* **Key Concepts Applied:** Defining custom tools for agents, robust function calling, error handling in agentic workflows.
* **Results:** Enhanced agent intelligence by providing access to a wider range of custom-defined actions, enabling more complex problem-solving.

---

## Setup & Dependencies:

To run these notebooks locally, ensure you have Python 3.9+ installed. You will also need an OpenAI API key (or other LLM API key configured with LlamaIndex).

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/building-agentic-rag-with-llamaindex.git](https://github.com/yourusername/building-agentic-rag-with-llamaindex.git)
    cd building-agentic-rag-with-llamaindex
    ```
2.  **Install dependencies:**
    It's recommended to create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
    (Note: A `requirements.txt` file should be generated by running `pip freeze > requirements.txt` after installing necessary packages for the course.)
3.  **Set your API Key:**
    Create a `.env` file in the root directory of the repository and add your OpenAI API key:
    ```
    OPENAI_API_KEY='your_openai_api_key_here'
    ```
    *Alternatively, set it directly in your environment variables.*
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

## Connect with Me:

* [Your LinkedIn Profile](https://www.linkedin.com/in/ali-adibnia)

---
