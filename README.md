# Medical RAG QA App

This repository contains the source code for the Medical RAG QA (Question Answering) Application, which utilizes Meditron 7B LLM (Language Model), Qdrant Vector Database, and PubMedBERT Embedding Model.

## Features

- **Question Answering:** Allows users to ask medical-related questions and get relevant answers from the integrated models.
- **Vector Database:** Utilizes Qdrant Vector Database for efficient storage and retrieval of medical data.
- **Embedding Model:** Leverages PubMedBERT Embedding Model for contextual understanding and accuracy in responses.
- **User-friendly Interface:** Provides an intuitive interface for easy interaction with the application.

## Requirements

- Python 3.x
- Meditron 7B LLM
- Qdrant Vector Database
- PubMedBERT Embedding Model
- Flask (for web interface)

## Installation

1. Clone the repository:


Certainly! Below is a sample README file for your Medical RAG QA App repository on GitHub:

markdown
Copy code
# Medical RAG QA App

This repository contains the source code for the Medical RAG QA (Question Answering) Application, which utilizes Meditron 7B LLM (Language Model), Qdrant Vector Database, and PubMedBERT Embedding Model.

## Features

- **Question Answering:** Allows users to ask medical-related questions and get relevant answers from the integrated models.
- **Vector Database:** Utilizes Qdrant Vector Database for efficient storage and retrieval of medical data.
- **Embedding Model:** Leverages PubMedBERT Embedding Model for contextual understanding and accuracy in responses.
- **User-friendly Interface:** Provides an intuitive interface for easy interaction with the application.

## Requirements

- Python 3.x
- Meditron 7B LLM
- Qdrant Vector Database
- PubMedBERT Embedding Model
- Flask (for web interface)

## Installation

1. Clone the repository:

git clone https://github.com/laggywiggl/medical-rag-qa-app.git


2. Install dependencies:

pip install -r requirements.txt



3. Set up Qdrant Vector Database:

- Install Docker if not already installed.
- Pull the Qdrant Docker image and run it with the appropriate configuration to store chunk vectors.

4. Configure models and database according to your setup.

## Usage

1. Run the application:

python app.py


2. Access the application through a web browser at `http://localhost:5000`.

3. Ask medical-related questions and get instant answers!

## Additional Data Storage

- Use the `data_pdf` folder to store any additional data you want to incorporate into the chatbot's knowledge base.

## Contributors

- OUAFA AIT OUAMER ([laggywiggl](https://github.com/laggywiggl))

## License

This project is licensed under the [MIT License](LICENSE).
