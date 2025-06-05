# Semantic Book Recommender with LLMs

This project develops a semantic book recommender system leveraging the power of Large Language Models (LLMs). It encompasses several key components:

## Project Components

* **Text Data Cleaning:** Preparing raw text data for effective use in language models.
* **Semantic (Vector) Search & Vector Database:** Building a system to find semantically similar books using vector embeddings and storing them in a dedicated database.
* **Text Classification with Zero-Shot Learning:** Performing text categorization without prior training examples for specific categories, utilizing LLMs' inherent understanding.
* **Sentiment Analysis & Emotion Extraction:** Analyzing the emotional tone of text and extracting specific emotions using LLMs.
* **Web Application with Gradio:** Creating an interactive user interface using Gradio for users to easily get book recommendations.

---

## Setup and Dependencies

This project was developed using **Python 3.11**. To run the project successfully, please ensure you have the following dependencies installed:

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

A `requirements.txt` file, containing all necessary project dependencies, is provided in this repository for easy installation. You can install them using pip:

```bash
pip install -r requirements.txt

