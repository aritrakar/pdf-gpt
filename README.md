# PDF-GPT

This is a simple application which allows you to upload your PDFs and then "chat" with them, as one does with ChatGPT. Experimenting with LangChain.

**Made with:**

- LangChain (Text splitting, generating embeddings, FAISS, Q&A chain)
- OpenAI's davinci-003 LLM (For "chatting")
- Streamlit (Web UI)
- PyPDF2 (For parsing the PDFs)

**NOTE:**

1. I tested with a paid organization account.
2. Each query costs some small amount, dependeing on the query complexity. It's usually between 2-5 cents.

# How to run locally

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Add a `.env` file with your `OPENAI_API_KEY`. **Do not rename this environment variable, otherwise LangChain will not work.**
4. Run the Streamlit application: `streamlit run main.py`
