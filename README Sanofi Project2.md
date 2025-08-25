# 🧪 Sanofi Project 2 : Clinical Trial Intelligence with SQL & Power BI 📊
**A portfolio project leveraging BigQuery, advanced SQL, and AI-powered tagging for trial insights**

---

## About the Project

This project extends the **Sanofi GRA/GRO portfolio** ([Project 1: GRA/GRO Performance](../README-Sanofi%20Project1.md)) and was designed to demonstrate my ability to handle large, messy real-world datasets with a strong focus on:

- **SQL proficiency** (BigQuery, advanced queries, partitioning, unnesting)
- **Data engineering** with Python, Power Query, and Google Cloud
- **AI-assisted data enrichment** (therapeutic area tagging using OpenAI & Ollama)
- **Advanced Power BI storytelling** with customized visuals, JSON themes, and parameters

The dataset chosen is the **WHO Clinical Trials Registry** (~105,000 trials over the last 5 years), offering a rich, global, and complex base to analyze.

---

## 🧠 Project Highlights

### Data Sourcing & Cleaning
- API initially explored but too inconsistent → **full database downloaded**
- Data cleaned and normalized using **Python notebooks** (`Sanofi_openai_ollama.ipynb`, `indications.ipynb`) and **Power Query**
- Final dataset: **~105,000 clinical trials** with normalized indications & therapeutic areas

### AI-Enhanced Tagging
- Used **OpenAI API** (free credits) and **Ollama** to classify therapeutic areas and indications from unstructured trial text (titles, comments)
- Applied post-processing to normalize indications into concise, consistent labels

### Cloud & SQL
- Clean dataset uploaded to **Google Cloud BigQuery**
- **SQL queries power 99% of the model**, with advanced techniques: `CTE (WITH)`, `PARTITION BY`, `UNNEST`, etc.

### Sanofi Branding & Design
- Extracted colors and fonts from **Sanofi's official PDF** to build a custom Power BI theme (`sanofi2.json`)

### Power BI Dashboards
- **Welcome Dashboard**: Author info, links to README/GitHub, plus an interactive **Vega globe** visualizing global trial volumes by country, build from scratch
<img width="1522" height="851" alt="image" src="https://github.com/user-attachments/assets/63e6cda4-0482-4e12-a685-ff3592d02202" />
- **SQL Skills Dashboard**: Demonstrates advanced SQL-powered visuals, built almost entirely on BigQuery logic
<img width="1517" height="851" alt="image" src="https://github.com/user-attachments/assets/d4758e09-f1bd-4b12-a511-b2ff792bcb50" />
- **Performance Dashboard**: Focuses on clinical trial approval times — compares Sanofi vs industry average by country and therapeutic area (with parameters, calculation groups, and R visuals)
<img width="1515" height="850" alt="image" src="https://github.com/user-attachments/assets/b44db902-99b9-463d-8792-dab6877ec0c5" />

[PBIX IS TOO BIG FOR GITHUB DOWNLOAD HERE](https://1drv.ms/u/c/57d3c64c25e64bc3/EYzcCRke4qpInbz1zlw_1oQBF9aeRmjDyC5Ou4NUiMDRUQ?e=JbLgXL)
---

## 📚 Technologies Used

- **Data Engineering**: Python, Power Query, Excel
- **AI/ML**: OpenAI API, Ollama (for tagging & classification)
- **Cloud & SQL**: Google Cloud, BigQuery, SQL (CTEs, partitions, unnest)
- **Visualization**: Power BI (DAX, Parameters, Calculation Groups, R, JSON theming), Vega
- **Collaboration**: GitHub repository (shared with [Project 1: GRA-GRO](../README-Sanofi%20Project1.md))

---

## 🔗 Related Projects

This project is part of a comprehensive Sanofi portfolio:
- **[Project 1: GRA/GRO Performance in Frozen Sectors](../README-Sanofi%20Project1.md)** - Veeva Vault RIM regulatory workflows simulation

---

## 📬 Contact

Created by **Roman Lakovskiy**  
Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/roman-lakovskiy/)  
or visit my portfolio: [https://roman-lakovskiy.ju.mp](https://roman-lakovskiy.ju.mp)

---
