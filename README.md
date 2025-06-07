This repository holds all the required code to build a semantic book recommender. The purpose of the files are as follows:

- data-exploration.ipynb : text data cleaning code
- vector-search.ipynb : building a vector database to facilitate similar book look ups
- text-classification.ipynb : classifying books as "fiction" or "non-fiction" using zero shot classification
- sentiment-analysis.ipynb : doing sentiment analysis using LLMs to extract the desired emotions of the book that user is looking for
- gradio-dashboard.py : a simple web interface for users to get book recommendations

  DATASET: "7k books" on Kagggle

  Required Dependencies :
  - kagglehub
  - pandas
  - matplotlib
  - seaborn
  - python-dotenv
  - langchain-community
  - langchain-opencv
  - langchain-chroma
  - transformers
  - gradio
  - notebook
  - ipywidgets
 
  You'll need to create .env file to store your OpenAI and Hugging Face API keys which will facilitate your vector database and one-shot classification respectively.

  To run the project and try the recommender yourself, launch the dashboard form gradio-dashboard.py.

  ![image](https://github.com/user-attachments/assets/8798ec00-2daa-4b4f-bfa8-92a9cc8e5e5b)
