# Hi, I'm Dhia Romdhane 👋

**Data Science & AI Engineering Student @ ESPRIT (Tunisia)**  
*Building reliable data pipelines, real-time ingestion services, and localized AI systems.*

[LinkedIn](https://linkedin.com/in/dhia-romdhane-ds) • [GitHub](https://github.com/dhia10) • [Email](mailto:dhia.romdhane@esprit.tn)  
*Sousse, Tunisia • Open to relocation • Seeking a 6-month End-of-Studies Internship (PFE) starting February 2027*

---

### 💡 About Me

I am a final-year engineering student passionate about solving practical data problems. Rather than chasing pure model scale, I focus on the end-to-end reliability of systems: ensuring high data quality at ingestion, designing clean backend microservices, and grounding LLM outputs to eliminate hallucinations. 

My daily stack revolves around **Python (FastAPI)**, **PostgreSQL**, **vector search (ChromaDB / NumPy)**, and **workflow automation (n8n, Docker)**.

---

### 🚀 Featured Projects

#### [shield_technology](https://github.com/dhia10/shield_technology)
*Enterprise security telemetry, vector search, and lead qualification platform.*
* **Architecture:** Built with clean hexagonal separation to keep core logic independent from frameworks and storage.
* **Telemetry & Ingestion:** Non-blocking in-memory ring buffer capturing client events with batch persistence.
* **Vector Search:** Lightweight, sub-1.5ms cosine similarity search powered by vectorized NumPy operations.
* **Reliability:** Auditable lead scoring engine backed by strict Pydantic schemas and 20/20 automated unit tests.
* **Stack:** Python 3.11, FastAPI, Pydantic, NumPy, SQLite, Docker, Pytest.

#### [EstateMind](https://github.com/dhia10/EstateMind)
*Real estate analytics platform combining valuation models and localized legal RAG.*
* **Hybrid Storage:** Multi-source ingestion pipeline routing financial data to PostgreSQL and unstructured listings to MongoDB.
* **Grounded Legal Assistant:** Local regulatory Q&A agent running on Ollama (`llama3.2`) and ChromaDB, strictly referencing Tunisian property laws.
* **Valuation Engine:** Supervised XGBoost pricing model integrated with OpenStreetMap spatial scoring and Mapbox GL.
* **Stack:** Python, FastAPI, Next.js 14, XGBoost, ChromaDB, Ollama, PostgreSQL, MongoDB.

#### [facebook-fetcher](https://github.com/dhia10/facebook-fetcher)
*Real-time stream parser and automated lead router for live commerce.*
* **Stream Parsing:** Continuous ingestion worker extracting phone numbers and purchase intent with operator prefix validation.
* **Sanitization & Deduplication:** Cleans Arabic-Indic digits and applies a 1-hour sliding cache to ignore repeat entries.
* **Business Impact:** Dispatches validated leads to n8n workflows, increasing daily capture throughput from 300 to 700 leads (+133%).
* **Stack:** Python, FastAPI, Pydantic, n8n, Webhooks, PostgreSQL, Docker.

#### [waste-sorter](https://github.com/dhia10/waste-sorter)
*Real-time computer vision sorting system (Clean & Green Hackathon — 4th Place & Honorary Award).*
* **Deterministic Vision:** Sub-15ms OpenCV inspection pipeline using edge detection, HSV color profiling, and specular glare analysis (Organic, Plastic, Metal).
* **Hardware Interfacing:** Synchronized classification outputs with physical sorting gates via Serial/HTTP protocols with cooldown filtering.
* **Stack:** Python, OpenCV, NumPy, Edge Inference, Serial / HTTP.

---

### 🛠️ Technical Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **Data Engineering** | PostgreSQL, MongoDB, SQLite, Web Scraping (Playwright, BeautifulSoup), Data Validation (Pydantic) |
| **Backend & Architecture** | Python (FastAPI, Flask), RESTful APIs, Clean Architecture, Docker, Git / GitHub Actions |
| **AI & Retrieval** | Local RAG, ChromaDB, Ollama, Prompt Grounding & Guardrails, OpenCV (Computer Vision) |
| **Automation & Analytics** | n8n Workflows, Webhooks, Power BI (DAX), Streamlit, Pandas, NumPy |

---

### 📜 Certifications

* **NVIDIA Deep Learning Institute:** Building RAG Agents with LLMs
* **Anthropic Claude Academy:** Building with the Claude API
* **Meta:** Data Analytics Professional Certificate
* **IBM:** Deep Learning & Data Science Methodologies
* **Microsoft:** Power BI Data Analyst Associate (PL-300 — Candidate)
* **Cisco Systems:** CCNA (Routing & Protocols)

---

### 📬 Get In Touch

* **Email:** [dhia.romdhane@esprit.tn](mailto:dhia.romdhane@esprit.tn)
* **LinkedIn:** [linkedin.com/in/dhia-romdhane-ds](https://linkedin.com/in/dhia-romdhane-ds)
* **GitHub:** [github.com/dhia10](https://github.com/dhia10)
* **Status:** Actively interviewing for **February 2027 PFE internships** (Sousse, Remote, or Relocation).
