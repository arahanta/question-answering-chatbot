# PDF-Based Chatbot
This module uses langchain-google-genai, pypdf, langchain, and chromadb to create a chatbot that can answer questions based on a PDF document.
## Functions
Functions

    handle_input(user_input): Handles user input and processes commands or questions.
    handle_command(command): Manages commands such as quitting or clearing history.
    handle_question(question): Addresses questions and provides answers based on the PDF document.
    initialize_vector_store(): Initializes the vector store for document indexing.
