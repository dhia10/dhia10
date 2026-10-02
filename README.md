# Dhia Romdhane

**Data Science & AI Engineering Student — ESPRIT (Tunisia)**  
*Focus: Real-Time Stream Ingestion, Local RAG Systems & Backend Architecture*  

[LinkedIn](https://www.linkedin.com/in/dhia-romdhane-ds/) • [GitHub](https://github.com/dhia10) • [Email](mailto:dhia.romdhane@esprit.tn)  
Sousse, Tunisia • Open to Relocation • Available February 2027 (6-Month PFE Internship)

---

## Technical Profile

I am an engineering student specializing in data engineering, applied AI, and backend services. I build systems prioritizing strict typing, data quality at ingestion, and deterministic software architecture over generative hype. My focus centers on low-latency streaming pipelines, grounded local RAG architectures, and clean service boundaries.

---

## Featured Proof of Work

### 1. [shield_technology](https://github.com/dhia10/shield_technology)
Enterprise security data platform built on layered Clean Architecture, decoupling business rules from external web frameworks and storage adapters. Processes telemetry beacons, vector similarity search, and automated RFQ lead qualification for commercial security operations.
- **In-Memory Ring Buffer & Telemetry Ingestion:** Engineered an asynchronous batch-flushing telemetry service capturing client beacon events with zero blocking on frontend interactions.
- **Vectorized Semantic Search:** Implemented cosine similarity search using vectorized NumPy operations, delivering sub-1.5ms query response times over catalog embeddings without external database overhead.
- **Deterministic Multi-Pillar Scoring:** Built an auditable lead and quotation scoring engine with strict Pydantic v2 schemas and HMAC-SHA256 authenticated webhook dispatch. 20/20 unit and integration tests passing in 0.16s.
- **Stack:** Python 3.11, FastAPI, Pydantic v2, NumPy, SQLite, Docker, Pytest.

### 2. [EstateMind](https://github.com/dhia10/EstateMind)
Real estate analytics platform structured around a hybrid database architecture and modular micro-services behind a centralized FastAPI gateway. Combines machine learning price estimation with a localized legal question-answering assistant for property regulations.
- **Distributed Ingestion & Hybrid Persistence:** Engineered multi-source scrapers consolidating property listings across regional portals into a dual storage model (PostgreSQL for financial records and metrics, MongoDB for raw descriptions and unstructured metadata).
- **Grounded Legal RAG Assistant:** Deployed a local regulatory assistant using ChromaDB semantic vector search and Ollama (`llama3.2`) with prompt grounding, ensuring strict citation of Tunisian property and tax law texts without hallucinations.
- **Valuation & Spatial Scoring:** Developed a supervised XGBoost price regression model on 15,000+ cleaned property records, integrated with OpenStreetMap (OSM) multi-criteria proximity scoring and Mapbox GL interactive visualizations.
- **Stack:** Python, FastAPI, Next.js 14, XGBoost, ChromaDB, Ollama, PostgreSQL, MongoDB, Mapbox GL.

### 3. [facebook-fetcher](https://github.com/dhia10/facebook-fetcher)
High-velocity stream ingestion worker and asynchronous REST service designed to capture incoming live commerce comments, sanitize payloads, and route verified prospect inquiries.
- **Entity Extraction & Pattern Matching:** Built an extraction engine parsing unstructured comment streams in real time, detecting 8-digit Tunisian phone numbers across valid operator prefixes (`2x, 3x, 4x, 5x, 7x, 9x`) alongside purchase intent keywords (`prix`, `livraison`, `commande`).
- **Unicode Sanitization & Deduplication:** Implemented automated conversion of Arabic-Indic digits (`٠-٩`) to ASCII numbers, paired with an in-memory sliding cache (3600s window) eliminating duplicate entries from recurring commenters.
- **Workflow Automation & Impact:** Dispatched sanitized lead payloads via authenticated webhooks into n8n workflows and database storage, increasing daily processing capacity from 300 to 700 qualified leads (+133% capture rate).
- **Stack:** Python, FastAPI, Pydantic, n8n, Webhooks, PostgreSQL, Docker.

### 4. [waste-sorter](https://github.com/dhia10/waste-sorter)
Deterministic computer vision pipeline developed in a 48-hour collaborative sprint during the Clean & Green Hackathon (**4th Place & Honorary Prize**). Automates solid waste sorting on a moving conveyor into three distinct recovery streams: organic, recyclable plastics, and metals.
- **Deterministic Feature Classification:** Built an OpenCV visual inspection pipeline combining Gaussian smoothing, Canny edge detection, HSV color space segmentation, specular highlight thresholding (metallic glare), and Laplacian variance for surface roughness.
- **Low-Latency Edge Processing:** Maintained sustained frame processing latency below 15ms on standard CPU (40+ FPS throughput), ensuring real-time detection without frame loss.
- **Physical Actuator Integration:** Synchronized detection outputs with mechanical sorting gates via Serial and HTTP interfaces, utilizing a 1.0-second cooldown filter to prevent multi-triggering as items cross the optical field.
- **Stack:** Python, OpenCV, NumPy, Edge Inference, Serial / HTTP.

---

## Technical Competencies

| Domain | Core Technologies & Tools |
| :--- | :--- |
| **AI & LLM Systems** | Local RAG, ChromaDB, Ollama, LangChain, Guardrails & Grounding, OpenCV |
| **Data Engineering** | PostgreSQL, MongoDB, SQLite, Web Scraping (Playwright, BeautifulSoup, Streaming), Data Quality & Sanitization (Pydantic) |
| **Backend & Automation** | Python (FastAPI, Flask), n8n Workflows, Docker, RESTful APIs, Git / GitHub Actions |
| **Analytics & BI** | Power BI (DAX, Star Schema), Streamlit, Pandas, NumPy |

---

## Verified Certifications

- **NVIDIA Deep Learning Institute:** Building RAG Agents with LLMs
- **Anthropic Claude Academy:** Building with the Claude API
- **Meta Professional Certificate:** Data Analytics Professional
- **IBM Professional Certification:** Deep Learning & Data Science Methodologies
- **Oracle Certified:** OCI AI Foundations Associate
- **Microsoft:** Power BI Data Analyst Associate (PL-300 — In Progress)
- **Cisco Systems:** Cisco Certified Network Associate (CCNA)

---

## Contact & Availability

- **Status:** Actively seeking an End-of-Studies Internship (Stage PFE — 6 months) starting **February 2027**
- **Email:** [dhia.romdhane@esprit.tn](mailto:dhia.romdhane@esprit.tn)
- **LinkedIn:** [linkedin.com/in/dhia-romdhane-ds](https://www.linkedin.com/in/dhia-romdhane-ds/)
- **GitHub:** [github.com/dhia10](https://github.com/dhia10)
- **Location:** Sousse, Tunisia (Open to international relocation & remote opportunities)
