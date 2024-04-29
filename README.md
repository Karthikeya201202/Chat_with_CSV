### CSV Analyzer with LLMs (Language Models)
This project aims to create an interactive application that analyzes a CSV file using Large Language Models (LLMs). The application integrates the OpenAI API (specifically, GPT-3) for natural language understanding and generation. 
We use Streamlit to build a user-friendly interface for querying the data.
### Features
1. CSV Data Analysis:
 Upload a CSV file containing relevant data (e.g., financial records, customer reviews, product details).<br />
 Explore the dataset asking different queries (e.g., filters, charts).<br />
2. Question-Answering with LLMs:
 Utilize the OpenAI API to create a question-answering agent.<br />
 The agent processes user queries and provides relevant answers based on the data in the CSV file.<br />
3.Integration Details:
 We use the create_pandas_dataframe_agent function from Langchain to process the  CSV data for answering the queries.<br />
 The DataFrame serves as the input for the LLM, allowing it to understand and respond to user questions.<br />
### Installation
Install the required packages: pip install -r requirements.txt<br />
## Set up your OpenAI API credentials:
Obtain an API key from the OpenAI website.<br />
Add your API key to a .env file:<br />
OPENAI_API_KEY=your_api_key_here
### Usage
 1.streamlit run app.py<br />
 2.Upload your CSV file using the app interface.<br />
 3.Ask questions related to the data (e.g., “What was the total revenue in Q2 2023?” or “Which product received the highest ratings?”).<br />
 4.The LLM-powered agent will provide answers based on the data.<br />
 

