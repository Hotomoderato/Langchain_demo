# Langchain_demo

## ChatPDF Demo: Embedding PDFs and Searching for Similarities with Azure OpenAI

The ChatPDF Demo is a project that uses LangChain, an open source library, to embed PDF files based on Azure OpenAI services. The demo then uses FAISS to search for similarities between questions and documents. Once the input content and question are entered, GPT-3.5 returns the results.

### Prerequisites
* Azure subscription with access to Cognitive Services and Azure Chat API
* Python 3.9 or higher
* Requirement Packages
    - `pip install PyPDF2`
    - `pip install faiss-cpu`
    - `pip install langchain`

### Getting Started
1. Input your PDF file.
2. OpenAI Embedding to embed the PDF file.
3. Input your question.
4. FAISS to search for similarities between the input question and the embedded PDF.
5. GPT-3.5 to return the results.
---
## Data analysis demo: CSV Agent to perform pandas dataframe

This demo showcases how to use the Langchain CSV Agent to perform data analysis on multiple CSV files.

### Prerequisites
* Azure subscription with access to Cognitive Services and Azure Chat API
* Python 3.9 or higher
* Requirement Packages
    - `pip install langchain`

### Getting Started
1. Input your CSV files.
2. Create an instance of the AzureChatOpenAI class
3. Create a CSV Agent instance
4. Use the agent to run a query
6. GPT-3.5 to return the results.

This demo shows how to use the Langchain CSV Agent to analyze data from multiple CSV files and get insights based on user queries. You can modify the input query to get different types of analysis based on your requirements.

---
## Contributing
Contributions to the Langchain Demo are welcome! If you would like to contribute, please fork the repository and submit a pull request. 
