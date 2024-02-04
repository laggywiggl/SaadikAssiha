# Medical Research Information Chatbot

This FastAPI application serves as a medical research information chatbot, utilizing various language models and vector databases for question answering.

## Features

- **Question Answering:** Utilizes language models to answer medical-related questions.
- **Vector Database:** Stores chunk vectors in Qdrant Vector Database.
- **Additional Data Storage:** Utilizes the `data_pdf` folder to store additional data for the chatbot.

## Requirements

- Python 3.x
- `chainlit` library
- `langchain` library
- `qdrant_client` library
- `fastapi` library
- `transformers` library
- `sentence-transformers` library

## Installation

1. Clone the repository:

git clone https://github.com/laggywiggl/medical-research-chatbot.git

2. Install dependencies:

pip install -r requirements.txt


3. Set up Qdrant Vector Database in Docker.

## Usage

1. Run the FastAPI application:

uvicorn main:app --reload

2. Access the application through a web browser at `http://localhost:8000`.

3. Ask medical-related questions and get instant answers!

## Additional Information

- The `data_pdf` folder is used to store any additional data you want to incorporate into the chatbot's knowledge base.

## Contributors

- OUAFA AIT OUAMER ([laggywiggl](https://github.com/laggywiggl))

## License

This project is licensed under the [MIT License](LICENSE).
