# 🤖 Agentic RAG for Python Code Smell Detection

This repository contains the implementation of an **Agentic Retrieval-Augmented Generation (RAG)** framework for detecting code smells in Python programs. It combines symbolic code analysis and LLM-based reasoning using hybrid retrieval and modular agents.

---

## 🧠 Project Highlights

- 📦 **Agent**: Code Smell Detection Agent with routing logic
- 🧪 **Datasets**: Publicly available from Zenodo  
  🔗 [Code Smell Dataset on Zenodo](https://zenodo.org/records/7512516)
- 🔍 **Retrieval**: Hybrid (Sparse + Dense)
- 🧠 **LLMs Used**:
  - GPT-4
  - DeepSeek Chat Model
- 📊 **Tasks**: Detect `Long Method` and `Large Class` smells in Python code
- 📈 **Evaluation**: Based on smell classification accuracy and LLM reasoning

---

## 📁 Repository Structure

| Folder       | Description                                      |
|--------------|--------------------------------------------------|
| `notebooks/` | Agentic RAG pipeline notebook                    |
| `README.md`  | Project overview and usage instructions          |

---
## ⚙️ Requirements
- Python 3.10+
- Required libraries:
  - `transformers`
  - `torch`
  - `llama-index`
  - `faiss-cpu`
  - `scikit-learn`
  - `pandas`, `numpy`
  - `matplotlib` (for evaluation plots)

---
## 🚀 Running the Notebook

1. Open the notebook:notebooks/AgenticRAG.ipynb
2. Load the dataset from Zenodo
3. Run all cells in the notebook to reproduce the pipeline: Preprocessing → Retrieval (Sparse + Dense) → Hybrid retrieval → Classification → Evaluation

## 👩‍💻 Author

**Bushra Salama Aljohani**  
Master's in Computer Science  
📧 [bushraaljohani97@gmail.com].

---

## 📄 License
This project is currently private for academic use only.  
If you are interested in collaboration, citation, or reuse, please contact the author directly.


