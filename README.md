## Natural Language Processing for Character Analysis
This project focuses on character analysis for books available on Project Gutenberg, leveraging various Natural Language Processing (NLP) techniques.

# Project Overview
The goal of this project is to extract and analyze descriptive phrases related to character appearances in books from Project Gutenberg. By applying NLP methods, the project aims to provide insights into character interactions and their portrayal throughout the text.

# Text Preprocessing
For text preprocessing, use the TORI.ipynb notebook. This notebook processes the EPUB files downloaded from Project Gutenberg using the TORI pipeline, which helps in simplifying and structuring the textual information.

#NLP Technology
The TORI pipeline's output is then processed using BookNLP, resulting in the following documents:

1. .book
2. .book.html
3. .tokens
4. .entities
5. .quotes
6. .suspense
These documents are used for further analysis to extract meaningful information about the characters.

# WORDNET
To explore and expand on the vocabulary related to character descriptions, use the wordnet.ipynb notebook. This notebook leverages WordNet to find synonyms, hypernyms, and hyponyms of selected words, enriching the analysis of character appearance phrases.

# Coreference Resolution
The coref.ipynb notebook is used to extract phrases related to the appearance of the top 3 characters in the book. Although basic coreference methods are applied, this step is crucial for accurately identifying and associating descriptive phrases with the correct characters.

# Social Network Analysis
The social_network.ipynb notebook is used to visualize the interactions between the top 10 characters. This visualization represents the strength of interactions, providing insights into the relationships between characters.

