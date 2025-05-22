AI Chat Model using Transformer Models

Project Description:

Developed an advanced conversational AI chatbot leveraging state-of-the-art transformer models (Llama2-70b, Mixtral 8x7B, Llama3-8b) through Groq’s API, addressing the limitations of general-purpose chatbots. Designed and deployed a user-friendly Streamlit-based web interface with robust features including model selection, parameter customization, document context integration, and conversation management.

Key Contributions:

Model Integration: Successfully migrated from Hugging Face’s unreliable Inference API to Groq’s API, ensuring stable access to high-performance LLMs while eliminating local GPU dependency.

UI Development: Built an intuitive Streamlit interface with dynamic controls for temperature, max tokens, and system prompts, enhancing user interaction and customization.

Document Context: Implemented document processing for PDF, DOCX, and TXT files, enabling context-aware responses by integrating uploaded content into prompts.

Conversation Management: Engineered chat history functionality with save/clear features, improving usability and coherence in multi-turn dialogues.

Performance Optimization: Achieved low-latency responses using cloud-based inference, with Llama3-8b delivering optimal balance between speed and quality.

Technologies Used: Python, Streamlit, LangChain, Groq API, Python-dotenv, document processing libraries.

Outcome: Delivered a scalable, lightweight solution that bridges the gap between powerful LLMs and practical applications, demonstrating adaptability in overcoming API reliability and UI design challenges. Future enhancements include fine-tuning support and multi-user authentication.
