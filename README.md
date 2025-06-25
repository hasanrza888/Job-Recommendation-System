# 💼 Job Recommendation System Based on Resume Content

This project is part of my NLP coursework and aims to build an intelligent recommendation system that suggests the most relevant job roles based on a candidate's resume.

## 🚀 Project Overview

The system analyzes the textual content of a resume using NLP techniques and recommends the top 5 job titles that best match the candidate's profile. It leverages Named Entity Recognition (NER), TF-IDF-based similarity scoring, and a real-world job description dataset to perform the recommendations.

## 🛠 Features

- 📄 Extracts skills, job titles, and experience from resumes
- 🔍 Uses NER and keyword matching for information extraction
- 🧠 Computes similarity with job descriptions using TF-IDF
- ✅ Returns top 5 job matches with relevance scores
- 🔤 Preprocessing pipeline to clean and normalize text

## 📂 Dataset Used

- **Job Descriptions:** [Djinni Recruitment Dataset (Hugging Face)](https://huggingface.co/datasets/lang-uk/recruitment-dataset-job-descriptions-english)
- **Resume:** Sample resume uploaded manually (PDF format)

## 🧰 Tech Stack

- Python
- spaCy (NER)
- pdfminer.six (PDF text extraction)
- scikit-learn (TF-IDF & Cosine Similarity)
- Pandas (data handling)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-recommendation-system.git
   cd job-recommendation-system
