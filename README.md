# TRACE-X — AI-Powered Cyberattack Reconstruction from Digital Evidence

**Tagline:** *Don’t Just Detect the Attack. Reconstruct the Story.*

*OPCODE IMPACT 2026 | Hackathon Submission*

*Team ID:* OPC006


## 1. Problem Statement

Cyberattacks often leave behind different types of digital evidence, including suspicious emails, malicious URLs, login records, IP addresses, network activity, and file-access logs. However, these pieces of evidence are usually stored separately, making it difficult for investigators to understand how an attack happened.

TRACE-X aims to connect these scattered digital clues and reconstruct a possible chronological story of a cyberattack.

## 2. Solution Title

**TRACE-X: AI-Powered Cyberattack Reconstruction from Digital Evidence**

## 3. Solution Description

TRACE-X is an AI-assisted digital forensics platform designed to analyze and correlate digital evidence from different sources.

The system extracts important entities such as email addresses, URLs, domains, IP addresses, users, devices, and timestamps. It then identifies possible relationships between these entities and arranges related events into a chronological timeline.

For example, TRACE-X may connect a suspicious email with a URL visit, an unusual login, and access to a sensitive file. These events can help investigators understand a possible attack sequence.

The platform aims to provide:

* **Email Threat Analysis:** Identifies potentially suspicious emails using machine learning and rule-based indicators.
* **Digital Evidence Correlation:** Connects related evidence from emails, login logs, network logs, and file-access records.
* **Attack Timeline:** Organizes related events chronologically.
* **Evidence Relationship Graph:** Displays connections between users, devices, IP addresses, domains, URLs, and files.
* **Explainable Findings:** Shows the evidence and indicators supporting the analysis.
* **Forensic Integrity:** Uses SHA-256 hashes to help verify whether evidence files have changed.

TRACE-X is designed to support investigators by organizing evidence and highlighting possible attack patterns. Its findings are advisory and require human verification.

## 4. Technology Stack

| Component                      | Technologies                               |
| ------------------------------ | ------------------------------------------ |
| Programming Language           | Python                                     |
| Data Processing                | Pandas, NumPy                              |
| Machine Learning               | Scikit-learn                               |
| Natural Language Processing    | TF-IDF and text-processing techniques      |
| Evidence Relationship Analysis | NetworkX                                   |
| Dashboard                      | Streamlit                                  |
| Data Storage                   | CSV files; MySQL as an optional database   |
| Development Environment        | Google Colab, Anaconda, Visual Studio Code |
| Version Control                | Git and GitHub                             |

## 5. Quick Start Guide

### Prerequisites

* Python 3.10 or later, using a version compatible with the selected libraries
* Git
* Visual Studio Code or another Python editor

### Step 1: Clone the Repository

```bash
git clone https://github.com/anusreemanikandan00/TRACE-X.git
cd TRACE-X
```

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 3: Install Dependencies

If a `requirements.txt` file is available in the repository, run:

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

Run the relevant notebook in Google Colab or Jupyter Notebook. Once the Streamlit dashboard has been implemented, it can be launched using:

```bash
streamlit run app.py
```

*Note: The exact run commands and required files may change as the project modules are integrated.*

## 6. Future Scope

* Integrate email, network, authentication, and endpoint evidence into a unified analysis workflow.
* Improve detection of phishing emails and suspicious URLs.
* Develop automated attack timeline and evidence-graph generation.
* Add interactive investigation features and downloadable forensic reports.
* Support larger datasets and database-backed evidence storage.
* Explore integration with security information and event management (SIEM) tools.
* Improve explainability, evidence traceability, and investigator feedback mechanisms.

## 7. Team Contributions

| Team Member         | Responsibility                                                                             |
| -----------         | ------------------------------------------------------------------------------------------ |
| Muhammed Irfan PK   | Evidence dataset creation, normalization, integrity verification, and manifest generation  |
| Anusree M           | Email threat analysis, machine learning, URL extraction, and threat indicators             |
| Chaithra S          | Evidence correlation, attack timeline, relationship graph, and attack-story reconstruction |
| Adarsh Mathew       | Streamlit dashboard, report presentation, and user interaction                             |

*Replace the member placeholders with the final team members' names.*

## 8. Tools Used

* Google Colab
* Anaconda
* Python
* Jupyter Notebook
* Visual Studio Code
* Git and GitHub
* Streamlit
* Scikit-learn
* NetworkX
* MySQL (optional)

## Project Status

TRACE-X is being developed as a modular digital forensics prototype. Individual components are developed separately and are intended to be integrated into a unified platform.

**Disclaimer:** TRACE-X supports digital investigation by organizing evidence and identifying possible relationships. Its results do not independently prove that a cyberattack occurred.
