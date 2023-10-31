# TL;DR? 
### Automatic Extractive Text Summarization using NLTK and BeautifulSoup in Python

This project showcases an advanced approach to automatic extractive text summarization. Leveraging NLTK (Natural Language Toolkit) in Python, we are tokenizing sentences, computing the weighted frequency of occurrence, and calculating sentence scores to generate concise and coherent summaries.

### Key Features:

- **Efficient Summarization:** The project uses NLTK's language processing capabilities to efficiently summarize text content by identifying the most critical sentences.
- **Weighted Frequency Analysis:** Sentences are scored based on the weighted frequency of their words, ensuring that the most significant sentences are included in the summary.
- **Top Sentence Extraction:** The top `N` sentences with the highest scores are automatically extracted to create a coherent summary.
- **Web Data Retrieval:** The system can fetch text content from web sources, such as Wikipedia articles, using the BeautifulSoup library.
