# Task_05_Descriptive_Stats

This repository contains my submission for **Research Task 05: Descriptive Statistics and LLMs**. The goal of this task was to analyze a small dataset using descriptive statistics and compare that with how a Large Language Model (ChatGPT) interprets and answers natural language questions based on the same data.

---

## 📂 Files in This Repository

| File Name                                      | Description                                                                 |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| `Premier_League_bar_Goals_Home.png`           | Bar chart of "Goals Home" column (top 10 values)                           |
| `Premier_League_bar_Away_Goals.png`           | Bar chart of "Away Goals" column                                           |
| `Premier_League_bar_home_possessions.png`     | Bar chart of "home_possessions" column                                     |
| `Premier_League_bar_away_possessions.png`     | Bar chart of "away_possessions" column                                     |
| `prompt_log.txt`                              | Log of LLM prompts and responses                                           |
| `qa_results.xlsx`                             | Manual evaluation comparing LLM answers with Python-generated answers      |
| `questions.txt`                               | 10 natural language questions used to prompt the LLM                       |
| `summary_without_grouping_Premier_League.xls` | Descriptive statistics summary (first 10 rows of dataset, no grouping)     |
| `Task_05_Descriptive_stats.ipynb`             | Python scripts used (first 10 rows of dataset, no grouping)                |

---

## 📊 Project Overview

- **Dataset Used**: Premier League 2022–23 season (not uploaded per assignment instructions)
- **Scope**: Used only the first 10 rows to fit within LLM input limits
- **Grouping**: No grouping used in this task; grouping by `stadium` will be explored in Task 06
- **Model Used**: ChatGPT (GPT-4)
- **Descriptive Statistics**:
  - Calculated mean, min, max, standard deviation, count, and most frequent value
  - Generated bar plots for 4 selected numeric columns
- **Prompt Design**:
  - Created 10 questions across 5 categories (Easy to Coaching Insight)
  - Used Python for validating answers to questions 5–8
  - Questions 9–10 are narrative and answered only by the LLM

---

## 🧠 Evaluation Method

- Answers to questions 1–4 were verified using the output from the summary file.
- Python scripts were written to calculate true answers for questions 5–8.
- LLM responses were evaluated manually and logged in `qa_results.xlsx`.
- Narrative insight questions (9–10) were not evaluated numerically.

---
