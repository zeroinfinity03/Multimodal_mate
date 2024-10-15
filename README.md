# Multimodal Mate

**Multimodal Mate** is an advanced web application that leverages artificial intelligence to process and understand various types of user inputs, including text, images, and documents. It combines the capabilities of the **Gemini 1.5 Flash** language model for multimodal processing with a **Retrieval-Augmented Generation (RAG)** pipeline powered by **LlamaIndex**, enhancing document-based query handling. This architecture provides an intuitive interface coupled with robust backend processing.

## Features

- **Multimodal Input Processing**: Seamlessly handles and interprets text, images, and documents.
- **Advanced Language Model**: Utilizes **Gemini 1.5 Flash** for state-of-the-art natural language understanding and generation.
- **RAG Pipeline**: Employs **LlamaIndex** for efficient document indexing and retrieval, enhancing the relevance and accuracy of responses.
- **Supported Document Types**: Processes PDFs, PowerPoint presentations (PPT), Excel spreadsheets (XLSX), CSV files, and JSON documents.
- **Responsive User Interface**: Built with **HTML**, **Tailwind CSS**, and **JavaScript** to ensure a smooth and intuitive user experience.

## Technologies Used

- **Backend**: [FastAPI](https://fastapi.tiangolo.com/)
- **Frontend**: HTML, Tailwind CSS, JavaScript
- **AI Model**: [Gemini 1.5 Flash](https://example.com/gemini-model) *(replace with actual link if available)*
- **Document Processing**: [LlamaIndex](https://llamaindex.readthedocs.io/en/latest/), SimpleDirectoryReader
- **Embedding Model**: [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)


## Setup and Installation



## Setup and Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/multimodal_mate.git
cd multimodal_mate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file in the root directory and add your API keys and other environment variables. Example `.env` content:

```env
GOOGLE_API_KEY=your_google_api_key_here
PERPLEXITY_API_KEY=your_perplexity_api_key_here
GOOGLE_APPLICATION_CREDENTIALS=credentials/google_cloud_credentials.json
```

### Run the Application

```bash
uvicorn main:app --reload
```

### Access the Application

Open your browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Usage

- **Visionary**: Provides real-time assistance for visually impaired users.
- **Multimodal Mate**: Handles text, image, and document-based queries.

## Troubleshooting

- **API Keys Issues**: Ensure that you have enabled the correct APIs in the Google Cloud Console.
- **Dependencies Issues**: Try updating `requirements.txt` and running `pip install -r requirements.txt` again.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

```

---

### **Explanation:**

1. **Project Title & Overview**:
   - Provides a clear and concise introduction to what **Multimodal Mate** is and its primary functionalities.

2. **Features**:
   - Breaks down the core functionalities into easily digestible sections, highlighting both the direct processing capabilities and the RAG pipeline.

3. **User Interface and Input Handling**:
   - Differentiates between frontend and backend responsibilities, detailing the technologies and frameworks used.

4. **Document Processing and RAG Pipeline**:
   - Explains the steps involved in handling and processing various document types, emphasizing the use of `SimpleDirectoryReader`, `LlamaIndex`, and embedding generation.

5. **Query Processing and Response Generation**:
   - Clarifies how different types of queries are handled, distinguishing between direct and document-related queries.

6. **Current Limitation & Proposed Solution**:
   - Transparently addresses the project's limitations and suggests a feasible enhancement, demonstrating critical thinking and foresight.

7. **Integration and Workflow**:
   - Provides a high-level summary of how user interactions flow through the system, ensuring clarity on the application's operation.

8. **Technologies and Components Used**:
   - Lists all the major technologies and components, giving recruiters and collaborators a quick overview of the tech stack.

9. **Setup and Installation**:
   - Offers step-by-step instructions to get the project up and running locally, making it easy for others to contribute or test.

10. **Usage**:
    - Briefly mentions the two main components or features of the application.

11. **Troubleshooting**:
    - Addresses common issues that users might face, providing solutions to ensure a smooth setup experience.

12. **Contributing**:
    - Encourages collaboration and provides a clear pathway for others to contribute to the project.

13. **License**:
    - Specifies the project's licensing, which is essential for open-source projects.

---

### **Additional Tips:**

- **Badges**: Consider adding badges at the top of the README for things like build status, license, or GitHub issues to make it more visually appealing and informative.

- **Table of Contents**: For longer READMEs, a table of contents can improve navigation. Example:

  ```markdown
  ## Table of Contents
  - [Overview](#overview)
  - [Features](#features)
    - [Direct Processing with Gemini 1.5 Flash](#direct-processing-with-gemini-15-flash)
    - [Retrieval-Augmented Generation (RAG) Pipeline for Document-Based Queries](#retrieval-augmented-generation-rag-pipeline-for-document-based-queries)
  - [User Interface and Input Handling](#user-interface-and-input-handling)
    - [Frontend](#frontend)
    - [Backend (FastAPI)](#backend-fastapi)
  - [Document Processing and RAG Pipeline](#document-processing-and-rag-pipeline)
    - [Document Ingestion](#document-ingestion)
    - [Data Standardization and Chunking](#data-standardization-and-chunking)
    - [Embedding Generation and Indexing](#embedding-generation-and-indexing)
  - [Query Processing and Response Generation](#query-processing-and-response-generation)
    - [Direct Queries (Text and Image)](#direct-queries-text-and-image)
    - [Document-Related Queries (RAG Pipeline)](#document-related-queries-rag-pipeline)
  - [Current Limitation](#current-limitation)
  - [Proposed Solution](#proposed-solution)
  - [Integration and Workflow](#integration-and-workflow)
    - [Workflow Summary](#workflow-summary)
  - [Technologies and Components Used](#technologies-and-components-used)
    - [Frontend](#frontend-1)
    - [Backend](#backend-1)
    - [Document Processing and Retrieval](#document-processing-and-retrieval)
    - [Language Model](#language-model)
  - [Setup and Installation](#setup-and-installation)
    - [Clone the Repository](#clone-the-repository)
    - [Install Dependencies](#install-dependencies)
    - [Environment Variables](#environment-variables)
    - [Run the Application](#run-the-application)
    - [Access the Application](#access-the-application)
  - [Usage](#usage)
  - [Troubleshooting](#troubleshooting)
  - [Contributing](#contributing)
  - [License](#license)
  ```

- **Images and Diagrams**: If you have diagrams or screenshots, include them to visually represent the project structure or workflow.

- **Badges Example**:

  ```markdown
  ![License](https://img.shields.io/badge/License-MIT-yellow.svg)
  ![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
  ![FastAPI](https://img.shields.io/badge/FastAPI-0.70.0-brightgreen.svg)
  ```

- **Contribution Guidelines**: If you have specific guidelines, consider adding a `CONTRIBUTING.md` file and linking to it.

---

Feel free to customize the README further based on additional details or preferences specific to your project!
