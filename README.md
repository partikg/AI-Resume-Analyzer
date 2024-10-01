# **AI Resume Analyzer**  
*An AI-Powered Tool for Resume Parsing, Keyword Analysis, and Recommendations*  

**Developed by Pratik Raut**

---

## 🌟 **Project Overview**  
This project uses **Natural Language Processing (NLP)** techniques to analyze resumes and provide insights, such as:

- Extracting important keywords.
- Clustering resumes by industry-specific terms.
- Offering recommendations, predictions, and analytics based on keyword matching.

### 🎯 **Key Objectives**  
- Parse and structure resume data into **tabular formats** (e.g., CSV).
- Provide **recommendations** to improve resumes.
- Generate **predictions** for job roles based on skills and experience.
- Deliver **analytics** on users' resumes and trends.
  
### 🔥 **Scope of Use**  
- **Companies** can use this to analyze resumes for insights.
- **Individuals** can receive feedback to enhance their resumes and test them on the platform.
- **Colleges** can use this tool to review student resumes before placements and get analytics.

---

## ⚙️ **Tech Stack & Features**  

### Frontend
- **Technologies**: HTML, CSS, JavaScript  

### Backend
- **Technologies**: Python, Flask  

### Database  
- **MySQL**  

### 🛠 **Modules and Features**  
1. **Client Features**  
    - Extract resume data: **Basic Info**, **Skills**, **Keywords**  
    - Provide **skills recommendations**, **job role predictions**, and **overall score**  
    - Access to **resume improvement tips**, **interview guides**, and more  

2. **Admin Features**  
    - View all applicants' data in a **tabular format**  
    - Download user data as CSV  
    - Get **analytics** (user ratings, resume scores, city, country, etc.)  

---

## 🚀 **Setup Instructions**  

Follow these steps to run the project:

1. **Clone the Repository**  
    ```bash
    git clone https://github.com/partikg/Resume-Analyzer.git
    ```

2. **Create a Virtual Environment and Install Requirements**  
    ```bash
    python -m venv venvapp
    cd venvapp/Scripts
    activate
    cd ../..
    pip install -r requirements.txt
    python -m spacy download en_core_web_sm
    ```

3. **Database Setup**  
    Create a database called `cv` and update the credentials in `App.py`.

4. **Run the Application**  
    ```bash
    streamlit run App.py
    ```

---

## 🛠 **Known Issues and Troubleshooting**  
- If you encounter a `GeocoderUnavailable` error, please check your **internet connection**.

---

## 📊 **Roadmap**  
- Add resume scoring criteria for skills and projects.  
- Expand field recommendations for **web**, **android**, **iOS**, and **data science**.  
- Add **user detail viewing** and other improvements.  

---

## 🤝 **Contributions**  
Feel free to open a pull request or suggest any changes!
"# AI-Resume-Analyzer" 
