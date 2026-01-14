# AWKWARD
Automated Workflow for Knowledge Wrangling, Analysis, Retrieval and Discussion

# 📌 What is AWKWARD?

AWKWARD is a local, reproducible assistant designed to help researchers query, compare, and understand their own scientific literature.

It ingests a collection of academic PDFs, indexes them semantically, and allows you to ask natural-language questions exclusively based on those documents, with explicit citations to the original articles.

No internet knowledge.
No hallucinated references.
Just your papers — intelligently queried.

# 🎯 Why AWKWARD?

During a PhD, literature grows faster than human memory.

AWKWARD aims to:

- centralize scientific articles in one place

- enable semantic search (by meaning, not keywords)

- assist with synthesis, comparison, and explanation

- remain transparent, traceable, and reproducible

- be simple enough to share within a lab

It is not a replacement for reading papers.

It is a tool to read them better and faster.

# 🧩 Core Features

📄 PDF ingestion (local folder)

✂️ Intelligent chunking (sections / size-based fallback)

🧠 Semantic embeddings

📦 Local vector database (FAISS)

💬 Question answering with a language model

📎 Explicit citations (article, section, page)

🔒 Answers constrained to the provided corpus

🚀 Typical Workflow

Add PDFs to data/pdfs/

Run the ingestion pipeline

Ask questions about your corpus

Receive structured, cited answers

Example questions:

Which papers use method X after 2020?

What are the main assumptions behind model Y?

Compare the conclusions of Smith et al. and Dupont et al.

Explain this method at a Master’s level.

# 🧪 Design Philosophy

Local-first: no mandatory cloud infrastructure

Transparent: every answer is traceable to source text

Modular: each step can be inspected or replaced

Lab-friendly: reproducible by other researchers

Minimal: no UI or infra complexity unless needed

AWKWARD favors robustness over flashiness.

# ⚠️ Limitations (by design)

PDFs must be machine-readable (OCR not included by default)

Figures and equations are handled as plain text

Quality depends on PDF formatting and chunking strategy

Not intended as a general-purpose chatbot
