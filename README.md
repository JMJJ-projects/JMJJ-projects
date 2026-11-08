# Hi, I'm John-Michael 👋

Master's student in **Computer & Network Systems** (Université d'Évry Paris-Saclay), working across
**security**, **cloud** and **machine learning**. I like understanding systems all the way down,
from compilers to formal verification.

🔎 **Open to a 6-month internship from February 2027** in AI, cybersecurity or software engineering.

🌐 Portfolio (EN / FR): **[jmjjprojects.com](https://jmjjprojects.com)**

## ⭐ Featured projects

| Project | What it is | Stack |
|---|---|---|
| 🧪 **[Simulation Agent](https://github.com/JMJJ-projects/sim-agent)** · *new* | Ask a simulation question in plain language: the agent writes Python, runs it in a locked-down Docker sandbox and repairs it from the error output. Runs on 4 GB local models or hosted ones, and works as an MCP server. Benchmarked on 36 tasks: repair loop 7→20/36 on a local 3B model, gpt-oss-120b 36/36 ([results](https://github.com/JMJJ-projects/sim-agent/blob/main/docs/eval_results.md)). | Python, LangGraph, Ollama, Docker, MCP |
| 🛡️ **[CVE Triage Agent](https://github.com/JMJJ-projects/cve-triage-agent)** | Answers "what should I patch first?" for a CVE, a code snippet or a whole dependency file. Priority comes from CISA KEV, EPSS and CVSS through fixed rules, never from the LLM; upgrade advice comes only from OSV. CLI, MCP server and a GitHub Action that comments on PRs ([demo](https://github.com/JMJJ-projects/cve-triage-agent/pull/2)). Evaluated on 300 recent CVEs; 665 tests. | Python, LangGraph, LangChain, SQLite, GitHub Actions, MCP |
| 🔐 **[StockageCloud](https://github.com/JMJJ-projects/StockageCloud)** | Team project (3 people, 2025) that I reworked solo in 2026: self-hostable cloud storage where every file is encrypted at rest (AES-256-GCM envelope encryption) and tamper-checked on download. CSRF protection, brute-force lockout, expiring share links, 25 tests, Docker. [Live demo](https://johnm123.pythonanywhere.com/mainpage) | Python, Flask, cryptography, SQLite |
| 🧮 **[On-the-fly CTL model checking](https://jmjjprojects.com/projects/ctl/poster.pdf)** | M1 research project: verifying CTL properties on acyclic Kripke structures without building the whole state space. Proofs of formula simplifications + C implementation. | C, formal methods |
| 📈 **[Exam score prediction (Kaggle)](https://github.com/JMJJ-projects/kaggle-exam-score)** | 2-level stacking ensemble (HGBR, XGBoost, Ridge, LinearSVR, RealMLP) on 630k rows. Public RMSE 8.624, top ~15% of ~4,300 teams. | scikit-learn, XGBoost, PyTorch |
| ⚙️ **[Mini-JS compiler & VM](https://github.com/JMJJ-projects/mini-js-compiler)** | JavaCC compiler from a JavaScript subset to stack-machine assembly, with constant folding and a virtual machine to run it. | Java, JavaCC |

<details>
<summary><b>More projects</b></summary>

- **[EduMind](https://github.com/JMJJ-projects/edumind)**: grade & exam platform: requirements, UML, Scrum, and clickable prototypes ([live demo](https://jmjjprojects.com/edumind/))
- **[Clustering IoT sensor data](https://jmjjprojects.com/projects/clustering/)**: K-means, hierarchical and spectral clustering on 62k smoke-detector readings
- **[Restaurant Petri net](https://jmjjprojects.com/projects/petri-net/report.pdf)**: discrete-event model of a fast-food restaurant
- **[Customer Analysis Dashboard](https://github.com/JMJJ-projects/Customer-Analysis-Dashboard)**: Python + SQL data insights for small businesses
- **[Wikicomptine](https://github.com/JMJJ-projects/Wikicomptine)**: real-time client–server document store in C with semaphores

</details>

## 🧰 Toolbox

**Languages:** Python · C · Java · SQL · JavaScript · HTML/CSS  
**Frameworks & tools:** LangGraph · LangChain · Flask · scikit-learn · XGBoost · PyTorch · pandas · JavaCC · Docker · Git · GitHub Actions · Linux  
**Fundamentals:** algorithms & data structures · networks (TCP/IP, VPN, firewalls) · applied cryptography · formal verification · UML & Scrum

Outside code I refurbish old laptops, play tabletop RPGs, and used to play club chess.

## 📫 Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-jmjjprojects.com-9a7650?style=flat-square)](https://jmjjprojects.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jmjj-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jmjj/)
[![Email](https://img.shields.io/badge/Email-johnjenyjeyaraj%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:johnjenyjeyaraj@gmail.com)
