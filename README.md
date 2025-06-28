# ai-resume-matcher
# 🔍 AI Resume Matcher

Match resumes to job descriptions using natural language processing (NLP) and cosine similarity — the same logic used by applicant tracking systems (ATS) and recruiting tools.

---

<p align="center">
  <img src="resume_matching_ai_image.png" width="600"/>
</p>
<p align="center"><i>AI-generated visualization of resume-to-job matching</i></p>

---

## 📊 Project Overview

This project simulates an intelligent hiring assistant that:
- Cleans and preprocesses resume and job data
- Converts text to numerical vectors using TF-IDF
- Calculates similarity scores using cosine similarity
- Visualizes matches in a heatmap
- Optionally generates AI imagery to illustrate system behavior

---

## 🛠️ Tools & Libraries

- Python + Colab
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- `diffusers` (Stable Diffusion via Hugging Face)
- Cosine similarity
- TF-IDF Vectorization

---

## 📁 How It Works

1. **Upload**: Two Excel sheets — one with resumes, one with job descriptions  
2. **Clean**: Text normalization (emojis, unicode, spacing, punctuation)  
3. **Vectorize**: Convert to TF-IDF vectors using a shared vocabulary  
4. **Match**: Use cosine similarity to find the best-fit job for each resume  
5. **Visualize**: Generate a heatmap to highlight similarity scores  
6. **Generate**: AI image using Stable Diffusion to enhance presentation

---

## 🧠 What I’d Add Next

- A Gradio app to upload your own resumes and get a live job match
- Model tuning to weight important resume keywords
- ATS compatibility layer for real recruiter workflows
- Resume enhancement suggestions based on job similarity gaps

---

## 💼 Built by

**Hope Johnson**  
Generative AI Consultant | Tech Adoption | Business Transformation  
[LinkedIn](https://www.linkedin.com/in/hopejohnson00) | [Email](mailto:hopejohnson00@gmail.com)

---
