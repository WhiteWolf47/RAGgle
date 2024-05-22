# RAGgle
Chainlit app for advanced RAG using llamaparse, langchain, qdrant and models from groq.

- [LlamaCloud](https://cloud.llamaindex.ai/)
- [Qdrant Cloud](https://cloud.qdrant.io/)
- [Groq Cloud](https://console.groq.com/)

# Setup

### create virtualenv
```
python3 -m venv .venv && source .venv/bin/activate
```

### Install packages
```
pip install -r requirements.txt
```

### Environment variables
All env variables goes to .env ( cp `example.env` to `.env` and paste required env variables)

### Run the python following files
```
python3 ingest.py
chainlit run app.py
```