# PalmQnA-Helper
PalmBot FAQ Assistant is an intelligent question-answering (QA) system designed to assist users in retrieving answers from a knowledge base. This project leverages advanced language models and vector retrieval techniques to provide accurate responses to user queries.

### Key Features

- **FAQ Knowledge Base:** Utilizes a CSV file containing frequently asked questions (FAQs) and their corresponding answers as the knowledge base.
- **Google Palm Language Model:** Employs the Google Palm language model for natural language understanding and response generation.
- **Vector Embeddings:** Implements Hugging Face embeddings for representing questions and answers as vectors in a high-dimensional space.
- **FAISS Vector Database:** Utilizes FAISS (Facebook AI Similarity Search) for efficient similarity search and retrieval of relevant answers.
- **Streamlit Interface:** Offers a user-friendly interface powered by Streamlit, allowing users to input questions and receive instant responses.

### How to Use

1. Install the required dependencies specified in the `requirements.txt` file.
2. Set up environment variables, including the Google API key and file paths, as specified in the `.env` file.
3. Run the `main.py` script to launch the Streamlit application.
4. Optionally, create the vector database by clicking the "Create Knowledgebase" button to preprocess and index the FAQs.
5. Input your questions in the provided text box and receive instant responses from PalmBot.

### Contributing

Contributions to PalmBot FAQ Assistant are welcome! Whether you want to enhance the functionality, improve performance, or fix bugs, feel free to fork the repository, make your changes, and submit a pull request.

### Acknowledgments

Special thanks to CodeBasics YouTube, OpenAI, Hugging Face, and the developers of FAISS for their invaluable contributions to the field of natural language processing and information retrieval.
