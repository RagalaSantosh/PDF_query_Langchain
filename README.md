**PDF Query Bot**
Welcome to the **PDF Query Bot** repository! This chatbot is designed to extract and query details from digital PDF files. Whether you’re analyzing research papers, legal documents, or user manuals, this bot can assist you in retrieving relevant information.

**Features**

**PDF Parsing and Extraction:**

1. The bot uses Langchain to parse PDF files and extract text content.
2. It leverages **OpenAI’s language models** to understand user queries.

**Querying PDF Details:**
1. Users can upload a PDF file.
2. The bot processes the file and allows users to ask questions related to its content.
   
**Customizable Queries:**
1. You can tailor the bot to handle specific types of PDFs (e.g., scientific articles, contracts, invoices).
2. Define custom queries or use predefined ones to extract specific information.

**Installation**
**Clone this repository:**
git clone https://github.com/RagalaSantosh/PDF_query_Langchain.git
cd PDF_query_Langchain

**Install dependencies:**
pip install -r requirements.txt

**Set up your API keys**:
Obtain an API key for OpenAI (if using their language models).
Create a .env file and add your API key:
  OPENAI_API_KEY=your_openai_api_key

**Run the bot:**
PDF_query.ipynb

**Usage**
1. Start the bot by running python bot.py.
2. Upload a PDF file using the provided command or interface.

**Ask questions related to the content of the PDF. For example:**
1. “What are the key findings in this research paper?”
2. “Show me the warranty terms in this user manual.”
3. 
The bot will process your query and provide relevant details from the PDF.
