Here’s a professional, clean README for your GitHub project based on the notebook `001_PDFQuery_LangChain_GROQ.ipynb`.

---

## 🧠 PDF Query Using LangChain + Groq + Astra DB

This project demonstrates how to build an intelligent document question-answering system using **LangChain**, **Groq LLMs**, and **Astra DB**. Users can upload PDF documents and query them conversationally with LLMs.

---

### 🚀 Features

* 📄 Upload and parse PDFs
* 🧠 Semantic search using **Astra DB** + **CassIO**
* 💬 Conversational querying with **Groq LLMs** (via `langchain_groq`)
* 🔗 Built on **LangChain**

---

### 🛠️ Installation



```bash
pip install cassio datasets langchain langchain_groq tiktoken
```

---

### 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your-groq-api-key
ASTRA_DB_APPLICATION_TOKEN=your-astra-db-token
ASTRA_DB_ID=your-astra-db-id
```

---

### 🧪 Usage

Launch the notebook:

```bash
jupyter notebook 001_PDFQuery_LangChain_GROQ.ipynb
```

---

### 📂 File Structure

```
📁 your-repo/
├── 001_PDFQuery_LangChain_GROQ.ipynb
├── .env                 # Your secret keys
├── requirements.txt     # Python dependencies
└── README.md            # Project description
```

---

### ⚠️ Notes

* Make sure you're using **Python 3.11** (not 3.12) as `cassio` and `cassandra-driver` have compatibility issues with 3.12.
* Your Astra DB must be properly configured with a vector-enabled keyspace.

---


