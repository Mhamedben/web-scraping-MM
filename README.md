# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

Objectives
Learn to scrape web pages and save the content to local files.
Process and analyze text data using Python libraries like BeautifulSoup and spaCy.
Visualize results through histograms and draw meaningful insights.
Tools and Libraries
The following tools and Python libraries were used in this project:

BeautifulSoup4: For web scraping and parsing HTML documents.
spaCy: For natural language processing, tokenization, and lemmatization.
Matplotlib: For visualizing sentence scores.
Requests: For fetching web pages.
Tasks
Web Scraping: Fetched and extracted an article's HTML using BeautifulSoup and saved it as a .pkl file.
Text Extraction: Loaded the saved HTML and extracted text content using BeautifulSoup's .get_text() method.
Token Analysis: Identified the 5 most frequent tokens, excluding stopwords, punctuation, and whitespace.
Lemma Analysis: Identified the 5 most frequent lemmas, with similar filtering.
Sentence Scoring: Scored sentences by their token and lemma occurrences, visualized the results using histograms.
Nouns-Only Analysis: Discussed how to filter and analyze only nouns using spaCy's POS tagging.
Visualizations
Histograms of sentence scores were plotted using Matplotlib to visualize the distribution of scores.
Challenges and Insights
Challenge: Filtering text to include only specific parts of speech (e.g., nouns).
Solution: Used spaCy's token.pos_ attribute for POS tagging.
Interesting Insight: The ability to extract meaningful insights by analyzing frequent tokens and lemmas in text.
How to Run the Project
Clone the repository:
git clone https://github.com/don4ye/web-scraping.git
