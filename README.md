# 🇮🇳 DataSevak: An Agentic Framework for Building India-Centric Datasets

**DataSevak** (from *Sevak* = helper/assistant in Sanskrit) is an intelligent, agent-powered framework that scrapes reliable public data from Indian government and verified sources, auto-generates high-quality Q&A or instructional datasets using LLMs, and prepares them for fine-tuning or RAG-based applications.

> 🧠 Your AI assistant that works like a digital public servant — gathering, structuring, and serving domain-specific knowledge for India.

---

## 🔍 Why DataSevak?

India has vast amounts of high-quality, publicly available information on domains like:

- ✅ **Finance & Tax** (RBI, SEBI, Income Tax Portal)
- ✅ **Healthcare** (MoHFW, NHP)
- ✅ **MSME & Startup Schemes** (msme.gov.in, udyamimitra.in)
- ✅ **Legal Rights** (nalsa.gov.in, indiacode.nic.in)
- ✅ **Agriculture** (agricoop.gov.in, pmfby.gov.in)
- ✅ **Education & Skilling** (NCERT, SkillIndia)

But this data is:
- Often locked in **unstructured HTML/PDFs**
- Not available in machine-tunable formats
- Largely **underutilized in AI applications**

**DataSevak solves this by automating**:
1. **Agentic scraping** from trusted sources
2. **Cleaning and chunking** content
3. **LLM-based generation** of Q&A, FAQs, summaries, or dialogue-style pairs
4. **Structured JSONL export** for training or retrieval pipelines

---

## 🚀 What Can You Build with DataSevak?

- 🧠 Finetune domain-specific LLMs (e.g., legal bot, MSME advisor)
- 🔍 Use generated data for **RAG pipelines** (MongoDB, FAISS, etc.)
- 🗣️ Create multilingual assistants (using translation or Indic LLMs)
- 📊 Analyze policy data across sectors
- 👥 Build public-serving AI tools for citizens

---

## 🛠️ Tech Stack

- **Python**
- **Selenium** / **trafilatura** for smart scraping
- **LangChain / Custom Agents** for planning & control
- **Open-Source LLMs** (e.g., Phi-2, TinyLlama) for QA generation
- **JSONL + Pydantic** for structured dataset creation
- Optional: **MongoDB**, **Gradio**, **FAISS** for downstream apps

---

## 🧩 Coming Soon

- [ ] `scrape.py`: Domain-specific scraper with selectors and source filtering
- [ ] `qa_gen.py`: Converts scraped text into structured Q&A format
- [ ] `finetune.py`: LoRA-based fine-tuning with generated dataset
- [ ] `rag_demo.py`: Mini RAG pipeline using generated dataset
- [ ] Gradio demo on Hugging Face Spaces

