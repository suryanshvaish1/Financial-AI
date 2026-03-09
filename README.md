# 🏦 Intelli-Credit: Next-Gen Corporate Credit Appraisal Engine

[cite_start]**A submission for The "Intelli-Credit" Challenge** [cite: 2]

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)](https://streamlit.io/)
[![Google ADK](https://img.shields.io/badge/Google%20ADK-0.1.0-orange.svg)](https://github.com/google/agent-development-kit)

## 📖 Overview
[cite_start]In the Indian corporate lending landscape, credit managers are overwhelmed by a "Data Paradox"—there is more information than ever, yet it takes weeks to process a single loan application[cite: 4]. [cite_start]Assessing the creditworthiness of a mid-sized Indian corporate requires stitching together disparate data points across structured formats (like GST filings and bank statements) and unstructured data (like annual reports and legal disputes)[cite: 5, 6, 7, 10, 11, 12, 22].

[cite_start]**Intelli-Credit** is an AI-powered Credit Decisioning Engine that automates the end-to-end preparation of a Comprehensive Credit Appraisal Memo (CAM)[cite: 28]. [cite_start]By leveraging Google's Agent Development Kit (ADK) and the Gemini AI model, this prototype bridges the intelligence gap by transforming fragmented multi-source data into explainable, actionable lending recommendations[cite: 3, 29].

---

## ✨ Key Features (The Three Pillars)

### [cite_start]1. The Data Ingestor (Multi-Format Support) [cite: 32]
* [cite_start]**Unstructured Parsing:** Extracts key financial commitments and risks from PDF annual reports, legal notices, and sanction letters[cite: 33].
* [cite_start]**Structured Synthesis:** Automatically cross-leverages structured data like GST returns against bank statements to identify anomalies such as "circular trading" or revenue inflation[cite: 34].

### [cite_start]2. The Research Agent (The "Digital Credit Manager") [cite: 35]
* [cite_start]**Secondary Research:** Automates the extraction of contextual data regarding sector-specific headwinds, litigation history, and promoter background[cite: 36].
* [cite_start]**Primary Insight Integration:** Provides a dedicated portal for the Credit Officer to input qualitative notes (e.g., observations from factory site visits or management interviews)[cite: 25, 37]. [cite_start]The AI adjusts the final risk score based on these nuances[cite: 38].

### [cite_start]3. The Recommendation Engine [cite: 39]
* [cite_start]**The CAM Generator:** Produces a professional, structured Credit Appraisal Memo summarizing the Five Cs of Credit (Character, Capacity, Capital, Collateral, and Conditions)[cite: 40].
* [cite_start]**Explainable Decision Logic:** Suggests a specific loan amount and interest rate using a transparent scoring model[cite: 41]. [cite_start]The AI explicitly explains why it recommended a rejection or a specific limit, ensuring it acts as a "glass box" rather than a black box (e.g., "Rejected due to high litigation risk found in secondary research despite strong GST flows")[cite: 42, 47].

---

## 🛠️ Technology Stack
* [cite_start]**Orchestration Framework:** Google Agent Development Kit (ADK) [cite: 1]
* [cite_start]**LLM / Intelligence Engine:** Google Gemini (`gemini-2.5-flash`) [cite: 1]
* [cite_start]**Frontend UI:** Streamlit [cite: 1]
* [cite_start]**Data Processing:** Python, Pandas, NumPy [cite: 1]
* [cite_start]**Data Visualization:** Plotly, Matplotlib [cite: 1]

---

## 🚀 Installation & Setup Instructions

To run this prototype locally, follow these steps:

### Prerequisites
* Python 3.10 or higher
* A valid Google Gemini API Key

### Step 1: Clone the Repository
```bash
git clone [https://github.com/yourusername/intelli-credit.git](https://github.com/yourusername/intelli-credit.git)
cd intelli-credit
