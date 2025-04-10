# 📊 Indian Job Postings Trend Analysis (Indeed | July–Sep 2021)

This project analyzes job posting trends on **Indeed India** between **July 1, 2021, and September 30, 2021**. The dataset contains raw job listings in JSON format collected over several weeks.
Link - https://www.kaggle.com/datasets/promptcloud/job-dataset-indeed-india/data

## 🔍 Project Goals

- Understand hiring trends based on frequency of posted roles
- Identify the **most and least posted job titles**
- Explore job descriptions to **filter roles by skills**
- Lay the groundwork for NLP-based job classification or skill extraction

---

## 🧰 Tech Stack

- Python
- Pandas
- JSON & zipfile handling
- Regular Expressions (Regex)
- Basic Natural Language Processing (NLP)

---

## 📌 Key Features

✅ Parse and clean raw JSON job data from compressed files  
✅ Count and rank job postings by frequency  
✅ Filter job descriptions using custom skill keyword lists  
✅ Analyze trends based on job titles, descriptions, and companies  

---

## 💡 Example Skill Filtering

Want to find jobs that mention `Python`, `SQL`, or `Machine Learning`?

```python
skills = ['python', 'sql', 'machine learning']
# The script dynamically filters descriptions that contain any of these skills.
