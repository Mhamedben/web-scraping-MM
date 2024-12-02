# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

# Name: Mhamed Maatou

# Copy and clone base repository

  1. Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner. The base repository is available at: https://github.com/wmnlp-materials/web-scrapingLinks to an external site.
  2. Clone YOUR new repo down to your machine.

# Installation

1. Activate virtual environment
   python -m venv .venv
   venv\Scripts\activate
   
2. Install the required packages:
    python -m pip install beautifulsoup4
    python -m pip install html5lib
    python -m pip install requests
    python -m pip install spacy
    python -m pip install spacytextblob 
    python -m pip install ipykernel
    python -m pip install matplotlib
    python -m pip install jupyterlab

# Tools and Libraries

    1. BeautifulSoup4: For web scraping and parsing HTML documents.
    2. spaCy: For natural language processing, tokenization, and lemmatization.
    3. collections: For counting word frequencies.
    4. matplotlib: For visualizing sentence scores.
    5. requests: For fetching web pages.

# Key Task

    1. Web Scraping: Extracted an article’s HTML using BeautifulSoup and saved it as a file.
    2. Text Extraction: Loaded the saved HTML and extracted text content using BeautifulSoup's .get_text() method.
    3. Token and Lemma Analysis: Found the 5 most freuent tokens and lemmas in the article (excluding stopwords, punctuation, and spaces).
    4. Sentence Scoring: Scored sentences by their token and lemma occurrences, visualized the results using histograms.
    5. Nouns-Only Analysis: Explained how to focus only on nouns for the analysis using spaCy’s part-of-speech tagging.
    6. Visualization: Created histograms to show the distribution of sentence scores.

 # Export to HTML

 Export Using Jupyter Menu more options (...) tap near outline in the home page of Jupyter Notebook and export as HTML.

 # Git add and commit

    git add file.
    git commit -m " Assignment completed"
    git push origin main


