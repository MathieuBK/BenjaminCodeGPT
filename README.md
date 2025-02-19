# BenjaminCodeGPT

BenjaminCodeGPT is a chatbot application that simulates a conversation with the French content creator and indie developer BenjaminCode. The chatbot provides valuable insights and advice on web development, entrepreneurship, and tech, drawing from BenjaminCode's experiences shared on his YouTube channel. It also has access to the transcriptions of all videos from BenjaminCode’s YouTube channel, which are used to provide context and support for the chatbot's responses. Additionally, it can help with specific questions related to VueJS and NuxtJS, as BenjaminCode is a passionate advocate for these technologies.

## Features

- Engage in a conversation with a chatbot that emulates BenjaminCode's communication style.
- Receive focused, practical, and direct web development and entrepreneurship advice.
- Access relevant snippets from transcriptions of BenjaminCode's YouTube videos to support the chatbot's responses.
- Get assistance with VueJS and NuxtJS-related queries, with direct links to relevant documentation.
- Utilize semantic search to find relevant content from video transcripts.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key
- Pinecone API key and environment details

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

If you have any questions or need assistance, please feel free to reach out to me directly. You can contact Mathieu Bekkaye via [this page](https://many.bio/mathieubk).


## Acknowledgments

- React for proving that Stockholm Syndrome also applies to front-end devs (Please, don't sue me 😱 !)
- Benjamin Code for his inspiring content and insights on dev entrepreneurship.
- OpenAI for their language models and embeddings.
- AssemblyAI for providing a great Whisper API DX.
- Langchain for their text processing tools.
- Pinecone for their semantic search capabilities.
- Streamlit for providing an excellent framework to build AI-powered applications.
- Merops SAS for supporting this project
- Python for being such an amazing language ❤️
