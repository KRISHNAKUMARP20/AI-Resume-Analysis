<div align="center">
  <h1>🌴 AI RESUME ANALYZER 🌴</h1>
  <p>A Tool for Resume Analysis, Predictions and Recommendations</p>
  <p>
    <small align="justify">
      Built with 🤍 by 
      <a href="#">Krishnakumar</a>
     </small>
  </p>
</div><br/><br/>

## About the Project 🥱
<div align="center">
    <p align="justify"> 
      A tool which parses information from a resume using natural language processing and finds the keywords, clustering them into sectors based on those keywords. 
      Lastly, it shows recommendations, predictions, and analytics to the applicant/recruiter based on keyword matching.
    </p>
</div>

## Enhancements 🚀
This updated version includes the following major enhancements:
- **Zero-Config Database**: Replaced MySQL with a local `sqlite3` database for instant out-of-the-box local deployment.
- **Modern UI Overhaul**: Injected custom CSS for a sleek gradient layout and modern UI elements.
- **Dynamic Animations**: Integrated `streamlit-lottie` for dynamic visual feedback and animations during resume parsing.
- **Dependency Fixes**: Fixed C-level dependencies by upgrading to an isolated Python 3.9 virtual environment and explicitly patching the `spacy` model installation.

## Tech Stack 🍻
- **Frontend/Backend**: [Streamlit](https://streamlit.io/) (Python)
- **Database**: SQLite3
- **NLP**: `pyresparser`, `nltk`, `spacy`
- **Animations**: `streamlit-lottie`

## Setup & Installation 🛠️

1. **Prerequisites**
   - Ensure you are running Python 3.9 (recommended for compatibility with `pyresparser` and `thinc`).

2. **Create a Virtual Environment**
   ```bash
   python3.9 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   pip install streamlit-lottie requests
   pip install setuptools<71
   ```

4. **Install Spacy NLP Model**
   ```bash
   pip install "https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.3.1/en_core_web_sm-2.3.1.tar.gz"
   ```

5. **Run the Application**
   ```bash
   cd App
   streamlit run App.py
   ```

6. Open your browser at `http://localhost:8501`. 

*(Note: The SQLite database `sra.db` will be automatically generated upon first run).*



# 🤖 AI Resume Analysis System

An **AI-powered Resume Analysis System** that automatically analyzes resumes, extracts important candidate information, identifies skills and qualifications, and evaluates how well a resume matches a given job role.

## 🚀 Features

* 📄 Resume upload and text extraction
* 🤖 AI-based resume analysis
* 🔍 Automatic skill extraction
* 🎓 Education and qualification analysis
* 💼 Work experience identification
* 📊 Resume scoring and evaluation
* 🎯 Job-role matching
* 💡 Skill-gap identification
* 📝 Resume improvement suggestions
* 📈 Candidate analysis dashboard
* 📑 Support for PDF resumes

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **NLP**
* **HTML, CSS, JavaScript**
* **MySQL**
* **Machine Learning**

## 🔄 How It Works

1. User uploads a resume.
2. The system extracts the resume text.
3. NLP techniques process and analyze the content.
4. Skills, education, experience, and other details are identified.
5. The system compares the candidate profile with the selected job role.
6. A resume score and matching analysis are generated.
7. The system provides recommendations to improve the resume.

## 🎯 Objective

The main objective of this project is to reduce manual resume screening by using **Artificial Intelligence and Natural Language Processing** to provide faster, consistent, and data-driven resume analysis.

## 🔮 Future Enhancements

* AI-generated resume improvement
* Multiple job-role recommendations
* ATS compatibility checking
* Interview question generation
* LinkedIn profile analysis
* Advanced LLM integration
* Recruiter dashboard
* Candidate ranking and filtering

