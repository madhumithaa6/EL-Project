# EL-Project
AI Powered Resume Ranker
#  🤖 Intelligent Resume Screening & 🔝 Candidate Ranking

**AIRecruit Pro** is a Streamlit-based web application that uses natural language processing (NLP) to intelligently rank resumes based on a provided job description. It leverages TF-IDF vectorization and cosine similarity to score and sort candidates, helping recruiters streamline their hiring process.

---

## 🚀 Features

- 📝 Accepts custom **job descriptions**
- 📤 Uploads multiple **resumes in PDF**
- 📊 Automatically **ranks resumes** based on relevance to the job
- ⚡ Built with **Streamlit**, **PyPDF2**, and **Scikit-learn**

---

## 🧠 How It Works

1. **Text Extraction**: Extracts raw text from uploaded PDF resumes.
2. **Vectorization**: Converts text data to numeric vectors using TF-IDF.
3. **Similarity Calculation**: Computes cosine similarity between each resume and the job description.
4. **Ranking**: Sorts resumes by relevance score in descending order.

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/madhumithaa6/EL-Project.git
   cd EL-Project
