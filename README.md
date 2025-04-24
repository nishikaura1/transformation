Document Processing & Entity Mapping

Tackle the **Document Processing and Entity Mapping** challenge. It compares structured logistics data from TMS JSON files with data extracted from markdown files, using large language models (LLMs) and similarity scoring to improve field-level matching accuracy.

---

## 🔍 Problem Overview

- Extract structured data from PDFs and markdowns (e.g., company name, address, invoice amount)
- Accurately map entity names despite rebrands, typos, or formatting inconsistencies
- Produce a normalized, production-ready output format
- Evaluate match accuracy and visualize results with a confusion matrix

---

## 🛠️ Approach

- **Extraction:** Used `pdfplumber` and regex for markdown and invoice field parsing
- **Normalization:** Applied GPT-4 for field-level normalization (e.g., cleaning, formatting)
- **Matching:** Used cosine similarity (TF-IDF) and alias fallbacks for robust company name matching
- **Error Logging:** Logged missing fields, low-confidence matches, and mismatches
- **Evaluation:** Output includes a CSV debug log and a seaborn-based heatmap




