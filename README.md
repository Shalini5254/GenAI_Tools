# GenAI Tools – LangChain Projects

A collection of hands-on Generative AI and LangChain projects exploring Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), vector databases, and AI-powered applications.

## 🚀 Projects

### 1. LangChain Crash Course
An introductory project exploring LangChain fundamentals and building applications using Large Language Models.

**Concepts Covered:**
- LangChain basics
- LLM integration
- Prompt templates
- Sequential chains
- AI-powered restaurant name generator

**Technologies:** Python, LangChain, OpenAI API

### 2. News Research Tool
An AI-powered research assistant that processes news articles and answers user questions using Retrieval-Augmented Generation.

**Features:**
- Load and process news articles
- Split text into manageable chunks
- Generate embeddings
- Store and retrieve information using FAISS
- Answer questions using LLMs

**Technologies:** Python, LangChain, OpenAI, FAISS, Streamlit

### 3. Codebasics Q&A
A question-answering application that retrieves relevant information from Codebasics FAQs and generates contextual responses.

**Features:**
- Document loading and processing
- Semantic search
- Vector embeddings
- FAISS vector database
- Context-aware question answering

**Technologies:** Python, LangChain, FAISS, Google Palm, Streamlit

### 4. SQL Database T-Shirt Assistant
An AI-powered application that converts natural language questions into SQL queries to retrieve information from a T-shirt sales database.

**Features:**
- Natural language to SQL conversion
- Database connectivity
- SQL query execution
- Sales data retrieval
- AI-powered responses

**Technologies:** Python, LangChain, MySQL, SQL, LLMs

## 🛠️ Technologies Used

- **Programming:** Python
- **AI & LLM:** LangChain, OpenAI, Google PaLM
- **Vector Database:** FAISS
- **Database:** MySQL
- **Data Processing:** Pandas
- **Application Framework:** Streamlit
- **Development Tools:** Jupyter Notebook, VS Code, Git, GitHub

## 📂 Repository Structure

```text
GenAI_Tools/
│
├── 1_langchain_crash_course/
│   ├── RestaurantNameGenerator/
│   ├── lanchain_crashcourse.ipynb
│   └── requirements.txt
│
├── 2_news_research_tool_project/
│   ├── notebooks/
│   ├── main.py
│   ├── README.md
│   └── requirements.txt
│
├── 3_project_codebasics_q_and_a/
│   ├── faiss_index/
│   ├── main.py
│   ├── langchain_helper.py
│   └── requirements.txt
│
├── 4_sqldb_tshirts/
│   ├── database/
│   ├── main.py
│   ├── langchain_helper.py
│   └── requirements.txt
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Shalini5254/GenAI_Tools.git
cd GenAI_Tools
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

Navigate to the required project directory and install its dependencies:

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

Create a `.env` file in the relevant project directory.

```env
OPENAI_API_KEY=your_api_key_here
```

Never upload API keys, passwords, or `.env` files to GitHub.

### 5. Run the application

For Streamlit applications:

```bash
streamlit run main.py
```

Follow the individual project README files for project-specific setup instructions.

## 🎯 Learning Objectives

- Understand Generative AI and Large Language Models.
- Build applications using LangChain.
- Implement Retrieval-Augmented Generation (RAG).
- Work with embeddings and vector databases.
- Integrate LLMs with SQL databases.
- Develop practical AI-powered applications.

## 👩‍💻 Author

**Shalini Thambutuku**

GitHub: [@Shalini5254](https://github.com/Shalini5254)

---

⭐ If you find these projects useful, feel free to explore and star this repository!

*Built as part of my journey in Generative AI, LangChain, and AI application development.*
