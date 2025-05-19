# **Semantic Book Recommender with LLMs**

This project is an **LLM** based applicated designed to recommend books on the basis of **NLP** techniques.
It uses techniques like **Semantic (vector) search** and also builds a vector database allowing users to find the most similar books using **natural language processing** queries.

## **Features**
1. Text Data Cleaning
2. Semantic (vector) search is done to the most relevant books relating to a specific category and also a vector database is built. This allows users to find the most similar books to a natural language query.
3. Uses text classification using zero-shot classification in LLMs from open source models. This allows us to classify the books as **"fiction" or "non-fiction"**, creating a facet that users can filter the books on.
4. Sentiment analysis is performed using open source LLMs and extracting the emotions from text. This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.
5. A web application using **Gradio** for users to get book recommendations.

## **Tech Stack**

1. **Programming Languages**: 
   - Python

2. **Libraries and Tools**:
   - **Gradio**: For building the web application.
   - **Vector Database**: For building vector database for the recommendation of books.
   - **Open Source Hugging Face LLM models**: For text classification using zero shot classification.
   - **Roberta**: For sentiment analysis.

## **Prerequisites**

Ensure the following are installed:

- Python 3.x
- Gradio
- Pandas
- Matplotlib
- Numpy
- Python-dotenv
- langchain-chroma
- transformers

## **Installation Steps**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/bhavyajethi/LLM-semantic-book-recommender.git

2. **Navigate to the project directory**:  
   ```bash
   cd LLM-book-recommender

3. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   
4. **Run the gradio Application**:  
   ```bash
   python app.py
