

## 🧠 PDF Query Using LangChain + Groq + Astra DB

This project demonstrates how to build an intelligent document question-answering system using **LangChain**, **Groq LLMs**, and **Astra DB**. Users can upload PDF documents and query them conversationally using powerful large language models.

---

### 🚀 Features

* 📄 Upload and parse PDFs
* 🧠 Semantic search using **Astra DB** and **CassIO**
* 💬 Conversational querying with **Groq LLMs**
* 🔗 Framework built using **LangChain**
* 🧠 Token-efficient processing with **Tiktoken**
* 📚 Integrated datasets via **Hugging Face Datasets**

---

### 📚 Libraries Used

| Library                     | Purpose                                                             |
| --------------------------- | ------------------------------------------------------------------- |
| **LangChain**               | Orchestrates LLM workflows, memory, agents, and chains.             |
| **CassIO**                  | Seamlessly integrates LangChain with Astra DB (vector database).    |
| **LangChain-Groq**          | Enables use of Groq's LLMs within the LangChain framework.          |
| **Groq API**                | Provides ultra-fast inference via Groq hardware-accelerated models. |
| **OpenAI Tiktoken**         | Efficient tokenizer for estimating token usage and cost.            |
| **Datasets (Hugging Face)** | Load sample documents and datasets for experimentation.             |

---

### 🛠️ Installation

```bash
pip install cassio datasets langchain langchain_groq tiktoken
```

---

### 🔐 Environment Setup

Create a `.env` file in your project root:

```env
GROQ_API_KEY=your-groq-api-key
ASTRA_DB_APPLICATION_TOKEN=your-astra-db-token
ASTRA_DB_ID=your-astra-db-id
```

Or export manually in your terminal:

```bash
export GROQ_API_KEY=your-groq-api-key
export ASTRA_DB_APPLICATION_TOKEN=your-astra-db-token
export ASTRA_DB_ID=your-astra-db-id
```

---

### 🧪 Usage

Launch the notebook:

```bash
jupyter notebook 001_PDFQuery_LangChain_GROQ.ipynb
```

---

### ⚠️ Python Compatibility

Use **Python 3.11**.
Python 3.12 removes the `asyncore` module, which causes compatibility issues with the Cassandra driver used by `CassIO`.

---

### 📂 File Structure

```
📁 your-repo/
├── 001_PDFQuery_LangChain_GROQ.ipynb
├── .env                 # Your secret keys
├── requirements.txt     # Python dependencies (optional)
└── README.md            # Project documentation
```

---

