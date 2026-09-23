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
