# BenjaminCodeGPT

BenjaminCodeGPT is a chatbot that simulates a conversation with [**Benjamin Code**](https://www.youtube.com/channel/UCLOAPb7ATQUs_nDs9ViLcMw), a French YouTuber and indie developer. It provides **practical advice** on **web development, VueJS, and tech entrepreneurship**, drawing from Benjamin's insights shared on his YouTube channel and SaaS project, [MeetSponsor](https://meetsponsors.com/).

The chatbot leverages semantic search and AI-powered video transcriptions to deliver context-aware responses, helping users navigate topics ranging from VueJS best practices to building and scaling a tech business.

## Features

- Engage in a conversation with a chatbot that emulates Benjamin Code's communication style.
- Receive focused, practical, and direct web development and entrepreneurship advice.
- Access relevant snippets from transcriptions of Benjamin Code's YouTube videos & VueJS documentation to support the chatbot's responses.
- Get assistance with **VueJS** and **NuxtJS**-related queries, with direct links to relevant documentation.
- Utilize semantic search to find relevant content from video transcripts.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key
- Pinecone API key and environment details
- MongoDB Atlas cluster with connection details

### Installation

1. Clone the repository:
```
git clone https://github.com/your-repo-url/BenjaminCodeGPT.git
```
2. Change to the project directory:
```
cd BenjaminCodeGPT
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Set up the environment variables:
- `OPENAI_API_KEY`: Your OpenAI API key
- `GROQ_API_KEY`: Your Groq API key
- `MONGO_DB_URI`: Your MongoDB URI connection string
- `MONGO_DB_DATABASE_NAME`: Your MongoDB database name
- `MONGO_DB_COLLECTION_NAME`: Your MongoDB database collection name
- `PINECONE_API_KEY`: Your Pinecone API key
- `PINECONE_ENVIRONMENT`: Your Pinecone environment details
- `PINECONE_INDEX_NAME`: Your Pinecone index details
- `PINECONE_ENDPOINT`: Your Pinecone endpoint


### Usage

1. Run the Streamlit app:
```
streamlit run app.py
```
2. Open the app in your web browser and enter your prompt to start the conversation with the chatbot. By default, Streamlit app will run on PORT 8501: 
- Local URL: http://localhost:8501
- Network URL: http://26.26.26.1:8501


## Contact

If you have any questions or need assistance, please feel free to reach out to me directly. You can contact Mathieu Bekkaye *via* [this page](https://many.bio/mathieubk).


## Acknowledgments

- **React** for proving that Stockholm Syndrome also applies to front-end devs (Please, don't sue me 😱 !)
- **Benjamin Code** for his inspiring content and insights on dev entrepreneurship.
- **OpenAI** for their language models and embeddings.
- **AssemblyAI** for providing a great Whisper API DX.
- **Langchain** for their text processing tools.
- **Pinecone** for their semantic search capabilities.
- **Streamlit** for providing an excellent framework to build AI-powered applications.
- **Merops SAS** for supporting this project
- **Python** for being such an amazing language ❤️
