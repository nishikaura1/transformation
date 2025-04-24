# TMS vs Markdown Field Comparison Tool

This project compares extracted logistics data from markdown files against structured data in JSON (TMS) format. The comparison uses normalization powered by GPT-4 to evaluate field accuracy, and results are visualized as a confusion matrix.

---

## 🧠 Key Features

- Extracts fields from logistics markdown files and TMS JSON files
- Normalizes values (company names, addresses, rates, etc.) using OpenAI GPT-4
- Performs fuzzy matching for companies based on associated address similarity
- Evaluates field accuracy with a True Positive / False Positive classification
- Outputs a CSV log and a heatmap-style confusion matrix of field comparison results

---

## 📁 Project Structure

