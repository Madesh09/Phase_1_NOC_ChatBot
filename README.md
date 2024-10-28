# NOC Chatbot Prototype

This project is a Retrieval-Augmented Generation (RAG) chatbot prototype designed to assist with Network Operations Center (NOC) tasks by answering specific, domain-related queries. The chatbot uses document embeddings and similarity-based retrieval to fetch relevant content and generate accurate responses.

## Features
- **PDF Document Loading**: Imports PDF files from a directory for knowledge extraction.
- **Text Splitting**: Splits large documents into manageable chunks for efficient processing.
- **Embeddings Generation**: Generates embeddings using `sentence-transformers` for semantic similarity.
- **Vector Storage**: Stores document embeddings in `Chroma` for quick retrieval.
- **Customized Prompting**: Tailors responses based on NOC-specific context using a structured prompt.
- **Hugging Face Model Integration**: Uses `mistralai/Mistral-7B-Instruct-v0.2` model from Hugging Face for natural language generation.

## Next Steps
- **Build Real-Time Prototype**: Transition from testing to a real-time deployment by developing a Streamlit-based interface in VS Code, enabling user-friendly interactions and live chatbot responses.
- **Optimize Model Parameters**: Experiment with temperature, response length, and other parameters for improved answer quality.
- **Expand Knowledge Base**: Incorporate additional domain-specific documents to enhance chatbot accuracy and relevance.
- **User Feedback**: Gather feedback to further refine the chatbot's responses and user experience.

