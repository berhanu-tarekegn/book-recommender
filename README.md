Semantic Book Recommender with LLMs

There are five components to this project:

Text data cleaning 
Semantic (vector) search and how to build a vector database
Doing text classification using zero-shot classification in LLMs
Doing sentiment analysis using LLMs and extracting the emotions from text
Creating a web application using Gradio for users to get book recommendations


This project was initially created in Python 3.11. In order to run the project, the following dependencies are required:

kagglehub
pandas
matplotlib
seaborn
python-dotenv
langchain-community
langchain-opencv
langchain-chroma
transformers
gradio
notebook
ipywidgets
A requirements.txt file containing all the project dependencies is provided as part of this repo.

In order to create your vector database, you'll need to create a .env file in your root directory containing your OpenAI API key and HuggingFace API key.
```
OPENAI_API_KEY=
HUGGINGFACEHUB_API_TOKEN=

```
The data for this project can be downloaded from Kaggle. Instructions on how to do this are also in the repo.
