# 📄 AI Resume Checker using NLP & OCR



## 🧠 Project Overview

The **AI Resume Checker** is an AI-based application that analyzes resumes and compares them with a given job description.  
It supports **image-based resumes (JPG/PNG)** using **OCR (Optical Character Recognition)** and evaluates resume relevance using **Natural Language Processing (NLP)** techniques.

This project is ideal for:
- 🎓 College Hackathons  
- 🤖 AI/ML Beginners  
- 📑 ATS (Applicant Tracking System) Demonstrations  

---

## 🎯 Problem Statement

Recruiters often receive thousands of resumes for a single job role.  
Manual screening is:

- ⏳ Time-consuming  
- ❌ Error-prone  
- ⚠️ Biased  

There is a need for an **automated system** that can efficiently evaluate resumes based on job requirements.

---

## 💡 Proposed Solution

The AI Resume Checker:
1. Accepts **resume images (JPG/PNG)**
2. Extracts text using **OCR**
3. Cleans and preprocesses text using **NLP**
4. Compares resume with job description
5. Generates:
   - 📊 ATS Score (0–100)
   - 🔍 Missing Skills
   - ✅ Resume Suitability Feedback

---

## 🚀 Features

- 📷 Image-based resume support (OCR)
- 🧠 NLP-based text processing
- 📊 ATS compatibility score
- 🔎 Skill gap analysis
- ⚡ Runs fully on Google Colab
- 👶 Beginner-friendly implementation

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Tesseract OCR**
- **Natural Language Processing (NLP)**
- **Machine Learning (TF-IDF, Cosine Similarity)**

---

## 📚 Libraries & Tools

### System Tool
- Tesseract OCR

### Python Libraries
- `pytesseract`
- `pillow`
- `nltk`
- `scikit-learn`

---

## 📦 Installation (Google Colab)

Run the following commands in a Colab notebook:

```bash
!apt-get install tesser
