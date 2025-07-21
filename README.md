# 🧪 Website URL Data Cleaning & Field Extraction

This project demonstrates a typical data preparation task I encounter in digital marketing analytics: transforming raw website URLs into structured fields for analysis.

While the dataset is fictitious, the logic and workflow reflect real-world challenges I solve in my role—especially when preparing datasets for Tableau dashboards or performance reporting.

---

## ✨ Before vs. After

![Before and After Screenshot] (before_after_fields.png) 

---

## 🎯 Objective

- Extract the **subfolder** (channel/category) and **page name** from raw URLs.
- Clean and format the page name to be human-readable.
- Simulate joining external data sources using `VLOOKUP` in Excel (and `merge()` in Python).
- Showcase analytical thinking and real-world Excel functions for transformation; despite not memorizing syntax, I find solutions with tools like Google or ChatGPT.

---

## 📊 Tools Used

| Excel Functions | Python Equivalents |
|-----------------|--------------------|
| `MID`, `FIND`   | `str.split()`, slicing |
| `SUBSTITUTE`, `TRIM` | `str.replace()`, `str.strip()` |
| `PROPER`        | `str.title()`      |
| `VLOOKUP`       | `pd.merge()`       |

---

## 🧰 Files Included

- `fictitious_website_analytics_dataset.xlsx` — The original dataset and formula-based transformations.
- `before_after.png` — Visual aid to show transformation steps.
