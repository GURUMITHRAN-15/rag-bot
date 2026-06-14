# RAG Customer Support Assistant

A simple Retrieval-Augmented Generation (RAG) application built using:

- LangChain
- ChromaDB
- Ollama
- Llama 3.1
- Nomic Embeddings

## Features

- Loads policy documents
- Splits documents into chunks
- Creates embeddings
- Stores vectors in ChromaDB
- Retrieves relevant information
- Answers user questions using Llama 3.1

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python rag.py
```

## Example Queries

### Example 1

**User Query:**

```text
How long does shipping take?
```

**Assistant Response:**

```text
Estimated delivery time: 3–7 business days.
```

---

### Example 2

**User Query:**

```text
I received a damaged product yesterday. Can I get a replacement?
```

**Assistant Response:**

```text
You can exchange the damaged product, but you need to raise your request within 7 days of delivery and replacement is subject to product availability.
```

---

### Example 3

**User Query:**

```text
What payment methods are accepted?
```

**Assistant Response:**

```text
We accept payments via credit card, debit card, net banking, and digital wallets.
```

---

### Example 4 (Out-of-Scope Question)

**User Query:**

```text
Do you accept cryptocurrency payments?
```

**Assistant Response:**

```text
The provided policy document does not contain information about cryptocurrency payments.
```

## Tech Stack

- Python
- LangChain
- Ollama
- ChromaDB
- Llama 3.1
- Nomic Embeddings

## Future Improvements

- Support PDF and DOCX documents
- Add conversational memory
- Build a Streamlit web interface
- Support multiple document collections
- Add source citations for retrieved answers
