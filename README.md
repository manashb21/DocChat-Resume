# DocChat-Resume: Resume Parsing and Question-Answering with AI

This project leverages state-of-the-art natural language processing models and techniques to parse resumes and automatically answer questions about the contents of a resume. By using a combination of text embedding models, document parsing, and a customized question-answering (QA) pipeline, the system is capable of answering various specific queries regarding resumes.

## Features

- **Resume Parsing**: Automatically loads and processes resumes from PDF documents.
- **Vector Database**: Uses **Chromadb** for storing and retrieving semantic vector representations of text for fast and efficient similarity searches.
- **Question Answering**: Uses **HuggingFace models** and a custom prompt to answer specific questions about the candidate, such as name, skills, education, experience, and more.
- **Customization**: Easily extensible to handle new types of questions or document formats.

