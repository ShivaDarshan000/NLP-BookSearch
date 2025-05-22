# NLP-BookSearch

📚 Book Search Engine (TF-IDF + NLP)
A simple, interactive search engine for books using Python, Pandas, and Natural Language Processing (NLP) techniques. Given a dataset of books, this project allows users to search for relevant titles and descriptions using TF-IDF-based ranking.

----------------------------------------------------------------------------------------------------

🚀 Features
Search for books by title, description, author, or publisher keywords

* TF-IDF-based ranking for relevant results

* NLP preprocessing: tokenization, stopword removal, lemmatization

* Easy-to-use interactive command-line interface

* Works with CSV book datasets (tested on Kaggle Books Dataset)

  ----------------------------------------------------------------------------------------------------

🛠️ Technologies Used
Python 3.x

Pandas

Numpy

NLTK (Natural Language Toolkit)

----------------------------------------------------------------------------------------------------

📦 Dataset
Download a books dataset in CSV format.

Link: https://www.kaggle.com/datasets/elvinrustam/books-dataset

Upload your dataset ZIP file (containing the CSV) to your environment (e.g., Google Colab, Jupyter).

----------------------------------------------------------------------------------------------------

⚡ How It Works
Extracts the CSV from your uploaded ZIP file.

Loads book data into a Pandas DataFrame.

Preprocesses text fields (title, description, etc.) using NLP techniques.

Builds a TF-IDF index for fast and relevant search.

Lets you search for books interactively by typing queries.

----------------------------------------------------------------------------------------------------

💡 Example
Search for books: python

1. Python in a Nutshell
   Ask any Python aficionado and you'll hear that Python programmers have it all: an elegant language that offers object-oriented programming support, a ...
   Score: 0.7946

2. Monty Python's Tunisian Holiday: My Life with Brian
   ...
   
----------------------------------------------------------------------------------------------------

📂 File Structure
book-search-engine/
│
├── book_search.py      # Main Python script
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

----------------------------------------------------------------------------------------------------

🧠 Concepts Used
Natural Language Processing (NLP): Tokenization, stopword removal, lemmatization

TF-IDF: For document ranking and relevance scoring

Information Retrieval: Simple search engine logic

