# 🌍 GDP Data Extraction and Processing

This project extracts the list of the top 10 largest economies in the world based on their GDP (in Billion USD) from the International Monetary Fund (IMF) via a Wikipedia page. The data is cleaned, processed, and stored as a CSV file using Python.

---

## 📌 Objective

To create a reproducible data pipeline that:
- Extracts GDP data from a web table.
- Processes it by selecting the top 10 countries.
- Converts GDP values from Million USD to Billion USD.
- Rounds values to 2 decimal places.
- Exports the cleaned data to a CSV file.

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- `pandas`
- `numpy`
- `lxml` (for HTML parsing)

---

## 🔗 Data Source

- [Wikipedia: List of countries by GDP (nominal)]([https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)](https://web.archive.org/web/20250106130614/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)))  
  *(Accessed through Web Archive to ensure consistency)*

---

## 📂 Files

| File                          | Description                               |
|------------------------------|-------------------------------------------|
| `GDP_Data_Extraction_and_Processing.ipynb` | Main Jupyter notebook with all code |
| `Largest_economies.csv`      | Cleaned CSV file with top 10 GDP values   |

---

