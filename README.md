![ss1](https://github.com/user-attachments/assets/451371c5-7590-404b-9085-27722c82f0c8)
# Healthcare Chatbot using Generative AI and NLP

This project is a healthcare chatbot designed to assist with symptom analysis by leveraging Generative AI and Natural Language Processing (NLP). The chatbot references a comprehensive medical dataset of 150 diseases, offering insightful medical advice for early symptom detection.

The core components include **Python**, **Flask**, **Google’s GEMINI API**, **Langchain**, and **ChromaDB** for managing vector embeddings from a PDF dataset. The chatbot runs on a Flask web server, providing users with an intuitive interface to interact with the medical knowledge base.

## Features

- **Natural Language Understanding**: Uses Google’s GEMINI API for interpreting user input.
- **Medical Dataset**: Utilizes a medical dataset in PDF format to provide advice.
- **Symptom Matching**: Performs accurate symptom analysis using vector embeddings.
- **ChromaDB Integration**: Stores vector embeddings in ChromaDB for efficient retrieval.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BhavyaShah7409/Healthcare-Chatbot.git
   cd Healthcare-Chatbot
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Create a .env file:
   ```bash
   GEMINI_API_KEY=your_api_key_here
4. Run the generate_embeddings.py file:
   ```bash
   python generate_embeddings.py
5. Run the app.py file:
   ```bash
   python app.py
6. The chatbot will be accessible on http://127.0.0.1:5000/
   

