# 📊 LLM-Powered EDA Automation

### Automated Data Insights using Mistral (Ollama) + Gradio

> Upload a CSV → Get descriptive stats, visualizations, and AI-generated insights instantly.

A fully automated Exploratory Data Analysis (EDA) system that combines traditional data analysis with **Large Language Model reasoning** to generate human-like analytical insights.

---

## 📌 Project Overview

This project bridges:

* 📊 Classical EDA (Pandas + Visualization)
* 🤖 LLM-driven Insight Generation (Mistral via Ollama)
* 🌐 Interactive UI (Gradio)

Instead of manually writing analysis code every time, users simply upload a CSV file and receive:

✔ Descriptive statistics
✔ Missing value summary
✔ Visualizations
✔ AI-generated natural language insights

This simulates how AI-assisted analytics tools will work in real-world data teams.

---

## 🖼 Application Preview

![Image](https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/gradio-guides/bigquery-dashboard.gif)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/0%2AWuDv8NM6cQfrDh4m.jpeg)

![Image](https://www.researchgate.net/publication/389210831/figure/fig1/AS%3A11431281311225431%401740166037466/The-summary-of-the-LLM-based-data-analysis-system-and-its-features-Given-a-task_Q320.jpg)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1200/1%2Aa7O1DMNtWhOpxyb2FbjJag.png)

---

## 🚀 Core Features

### 📋 Automated Descriptive Statistics

* Count
* Mean
* Median
* Standard deviation
* Min / Max

Generated instantly using Pandas.

---

### 🔍 Missing Value Analysis

* Column-wise missing count
* Percentage of missing values
* Data quality summary

---

### 📊 Visualization Engine

* Histograms for numeric columns
* Correlation heatmaps
* Clean, auto-generated plots

Built using:

* Matplotlib
* Seaborn

---

### 🤖 AI-Generated Insights (Mistral via Ollama)

The LLM analyzes:

* Statistical summaries
* Missing value patterns
* Distribution trends
* Correlation structure

Then produces:

* Business-style insights
* Pattern observations
* Potential anomalies
* Suggested next steps

This transforms raw data into narrative intelligence.

---

## 🧠 System Workflow

```
CSV Upload
    ↓
Data Cleaning (Pandas)
    ↓
Statistical Summary
    ↓
Visualization Generation
    ↓
LLM Prompt Construction
    ↓
Mistral (Ollama) Insight Generation
    ↓
Display Results in Gradio UI
```

---

## 🛠 Tech Stack

| Layer           | Technology           |
| --------------- | -------------------- |
| Language        | Python               |
| Data Processing | Pandas               |
| Visualization   | Matplotlib + Seaborn |
| LLM Engine      | Mistral (via Ollama) |
| UI              | Gradio               |

---

## ⚙️ Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/llm-eda-insight-generator.git
cd llm-eda-insight-generator
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Install & Run Ollama

Install Ollama and pull Mistral:

```bash
ollama pull mistral
```

Run Ollama locally.

---

### 4️⃣ Launch Application

```bash
python app.py
```

Gradio interface will open in your browser.

---

## 🎯 Ideal Use Cases

* 📊 Rapid dataset understanding
* 🧪 Academic EDA assignments
* 📈 Data analyst workflow automation
* 🤖 AI-powered analytics prototyping
* 📦 Business insight generation

---

## 📈 Why This Project Stands Out

This project demonstrates:

✔ Integration of classical data science + LLMs
✔ Prompt engineering for structured data
✔ Practical AI automation
✔ Clean UI + backend pipeline
✔ Real-world analytics workflow thinking

It shows understanding beyond “just plotting graphs” — it automates reasoning.

---

## 🔮 Future Enhancements

* 📂 Multi-file dataset comparison
* 📊 Interactive Plotly dashboards
* 🧠 Advanced anomaly detection
* 📥 Export AI insights as PDF report
* 🌍 Cloud deployment (Hugging Face Spaces / Docker)
* 🔐 Role-based dashboard access

---

## 🏗 Project Structure

```
llm-eda-insight-generator/
│
├── app.py
├── requirements.txt
├── utils/
└── README.md
```

---

## 👨‍💻 Author

**Tanmay Kshirsagar**

This project reflects a strong intersection of:

* Data Analytics
* Generative AI
* Automation
* Product mindset

---

## ⭐ Support

If this project helped you, consider giving it a ⭐ on GitHub.

---

