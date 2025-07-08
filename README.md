# Abhisht Joshi

Hi, I’m **Abhisht Makarand Joshi**, a software developer and machine learning researcher with a love for solving real-world problems using code, AI, and clean design. I’ve built NLP systems that flag at-risk students, real-time classifiers for DNS attacks, and dashboards that actually get used.

*Resume available <a href="https://drive.google.com/file/d/1-U18dsGxCAcxBIj_f8hDVlQJkD4nZPb5/view?usp=sharing" target="_blank">here</a>*

---

## 🔧 Technical Toolbox

**Languages**  
Python • Go • Java • C++ • SQL (MySQL, PostgreSQL)

**Frameworks & Tools**  
TensorFlow • PyTorch • HuggingFace • LLMs • Explainable AI (SHAP) • Streamlit • Flask • Spring Boot  
Git • Docker • AWS (EC2, S3, Lambda, Sagemaker, Cognito) • Azure DevOps • Kafka • Airflow  
MLOps (DVC, MLflow) • Tableau • PowerBI • Postman • PySpark • Hadoop

---

## 💼 Work Experience

**🔹 Health Canada – Software Developer**  
*Dec 2024 – Present*  
• Contributed to the development and maintaining the frontend of the National Vaccine Catalogue (NVC) using
React, HTML, and CSS, enhancing user experience and interface responsiveness for 1000+ users.

• Engineered backend services with Go, integrating APIs and optimizing system performance; utilized Azure
DevOps for CI/CD pipelines and deployment management.

**🔹 Department of Family Medicine, uOttawa – ML Developer**  
*May 2023 – Dec 2024*  
• Spearheaded the development of a health dashboard and a proof-of-concept of natural language processing
system to anticipate educational problems by mining data from the past 4 years, leveraging AI technology.

• Implemented and configured AWS Cognito OAuth2 Resource Server and JWT verification for secure user
authentication and authorization in a Spring Boot application.

• Implemented 5 ML models, 1 DL model (LSTM) and fine-tuned a language model XLNET (LLM). Improved
the detection accuracy by 14% as validated by medical experts using SHAP, an explainable AI technique.

**🔹 Environment Canada – Programmer Analyst**  
*Sep 2023 – Dec 2023*  
• Engineered Python scripts to extract data from various APIs as per user requirements and design solutions,
achieving a significant run time reduction from 3.5 minutes to 48 seconds.

• Integrated 6 Python scripts into a user-friendly Graphical User Interface (GUI) using PyQt5, enhancing data
visualization and accessibility. Implemented QA testing to assure the stability of the GUI.

• Diligently debugged, performed exception handling, and resolved over 50 errors in Python scripts, ensuring
smooth and error-free functionality, resulting in a 20% increase in overall system stability and performance.

**🔹 ZS Associates – Tech Solutions Intern**  
*Feb 2022 – Jul 2022*  

• Contributed to the seamless migration of 5000+ clinical studies and associated content to the new Clinical
Data Repository and Statistical Computing Environment (CDR-SCE) system, enabling a state-of-the-art
environment for data scientists.

• Automated the migration of 1000+ folders from the enterprise data lake to the target location in Amazon S3,
streamlining the data migration process.

---

## 📚 Education

**University of Ottawa**  
*Master’s in Computer Science (Applied AI)*  
GPA: 9.1/10  
Relevant: NLP, ML, AI for Cybersecurity, Ethics in AI

**MAIT (GGSIPU), Delhi**  
*B.Tech in Information Technology*  
GPA: 9/10  
Relevant: DS & Algos, Cloud Computing, Networks

---

## 🧠 Projects

---

### 🛰️ Dynamic DNS Exfiltration Attack Classification  
A real-time system that detects data exfiltration attacks using DNS traffic patterns.  
I built a producer in Docker that streamed **10,000+ DNS queries/sec** to Kafka. Then, I created a Kafka consumer that classified them in real-time using a sliding window. Achieved **90% accuracy** and an **85% F1 score**.

**Tools & Tech:** Python • Kafka • Docker • Scikit-learn  
📂 <a href="https://github.com/abhishtjoshi/DNS-Exfiltration-Attack-Classification" target="_blank">GitHub Repo</a>  
📷 `![DNS Attack Demo](assets/dns-attack.png)`

---

### 🧬 Cancer Classification using Medical Texts  
Built a text classification system to categorize cancer cases using clinical notes. Applied heavy NLP preprocessing—tokenization, cleaning, stopword removal—and implemented various ML & DL models, including LSTM and fine-tuned **BioBERT**. Achieved **98% accuracy** and **0.99 F1 score**.

**Tools & Tech:** Python • NLP • BioBERT • LSTM • Scikit-learn  
📂 <a href="https://github.com/abhishtjoshi/Cancer-Classification-using-Medical-Cancer-Text-Documentation-based-on-Machine-Learning-Model-and-NL" target="_blank">GitHub Repo</a>  
📷 `![Cancer Classifier](assets/cancer-classification.png)`

---

### 🍷 Wine Quality Prediction using MLOps  
Not just another ML model—this was an end-to-end pipeline. I used **DVC** for versioning, added **GitHub workflows** for CI/CD, and deployed the Random Forest model on **Heroku**. The app had YAML-driven param tuning and passed tests using **Pytest** & **Tox**. Achieved **RMSE: 0.23**.

**Tools & Tech:** Python • DVC • CI/CD • Heroku • Pytest • Random Forest  
📂 <a href="https://github.com/abhishtjoshi/Wine-Quality-Prediction-using-ML-and-DVC" target="_blank">GitHub Repo</a>  
📷 `![Wine Quality](assets/wine-quality.png)`

---

### 🎬 IMDb Sentiment Analysis Web App  
Built an RNN-based sentiment classifier for movie reviews. Trained the model on **Amazon SageMaker**, exposed it using an **API Gateway**, and created a minimal web frontend. Final app could classify text in real-time with **86% accuracy**.

**Tools & Tech:** PyTorch • AWS Sagemaker • API Gateway • Flask • HTML/CSS  
📂 <a href="https://github.com/abhishtjoshi/Project--Sentiment-Analysis" target="_blank">GitHub Repo</a>  
📷 `![IMDb App](assets/imdb-sentiment.png)`

---

### 📊 Student Performance Dashboard  
Designed an interactive dashboard that made student test data visual and meaningful. Cleaned messy CSVs, transformed them using **Power Query**, and added DAX measures for drill-down insights. Published to **Power BI Service** with auto-refresh and export support.

**Tools & Tech:** Power BI • DAX • Power Query  
📷 `![Student Dashboard](assets/student-dashboard.png)`


## 📄 Publications

- **Joshi, A.**, *CatBoost: An Ensemble Machine Learning Model for Prediction and Classification of Student Academic Performance.*  
  Indexed in ESCI. Focused on early academic risk prediction using ensemble learning.  
  🔗 <a href="https://www.worldscientific.com/doi/10.1142/S2424922X21410023" target="_blank">Read here</a>

- **Joshi, A.**, *An Effective Approach for Heart Diseases Prognosis Using Machine Learning Techniques.*  
  Published in LNNS (Springer). Used classification algorithms for prognosis prediction.  
  🔗 <a href="https://link.springer.com/chapter/10.1007/978-981-19-3148-2_69" target="_blank">Read here</a>

- **Joshi, A.**, *Early Prognosis of Acute Myocardial Infarction Using Machine Learning Techniques.*  
  ICDAM Conference. Focused on early prediction using EDA + ML.  
  🔗 <a href="https://link.springer.com/chapter/10.1007/978-981-16-6285-0_63" target="_blank">Read here</a>

---

## 🧾 Certifications

- Prompt Engineering – *LinkedIn Learning*  
- ML Engineer – *Udacity*  
- Machine Learning & Deep Learning – *Coursera*

---

## ✨ Extras

- 🏓 Table Tennis Champ – MAIT Annual Sports Meet  
- 🧠 AI/ML Head – Computer Society of India, MAIT  

---

## 📬 Get in Touch

**Email:** [abhishtjoshi04@gmail.com](mailto:abhishtjoshi04@gmail.com)  
**GitHub:** [abhishtjoshi](https://github.com/abhishtjoshi)  
**LinkedIn:** [abhishtjoshi16](https://www.linkedin.com/in/abhishtjoshi16/)

---

> “The goal is not to be better than anyone else... but to be better than you were yesterday.”
