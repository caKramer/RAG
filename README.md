# RAG

Python implementation of RAG utilizing Hugging Face.
Beautiful Soup for scraping Wikipedia Page - add any URL you wish to use.
Use FAISS for similarity search for vectors.

Other things to try: use a PDF or any other file desired for testing the RAG

Using Google Colab made this easy. Will work locally as well. 

## Steps

1. Create function to use BeautifulSoup to scrape wikipedia
2. Chunk the data from the wikipedia page
3. Generate embeddings and vector index
4. Retrieval function
5. Then use Hugging Face model: google/flan-t5-large
6. Tokenize
7. Create Chatbot for asking questions about the article
  - Contains example questions, source citations for RAG provided answers
  - Included analysis on correctness of the RAG responses


