# HireScope – AI-Powered Resume Analyzer

HireScope is an intelligent AI-driven resume analysis system designed to help users improve the quality, structure, and effectiveness of their resumes. It extracts important information, evaluates skills, recommends improvements, and provides actionable insights for both users and recruiters.
---

##  Features

### 📄 Resume Parsing
Automatically extracts:
- Skills  
- Experience  
- Education  
- Contact details  
- Achievements  
- Additional resume attributes  

###  Resume Scoring
Generates a structured score based on:
- Content quality  
- Formatting  
- Skill relevance  
- Resume completeness  

###  Skill Recommendations
Suggests additional relevant skills to strengthen the resume.

###  Course Recommendations
Recommends courses based on missing or weak skills.

###  User Level Assessment
Identifies whether the user is:
- Beginner  
- Intermediate  
- Advanced  

###  Admin Dashboard
Provides administrators with:
- User analytics  
- Skill trends  
- Parsed resume insights  
- Visual graphs  

---

##  Technologies Used

- **Python** – Core logic and backend  
- **Streamlit** – Web interface  
- **PyResparser** – Resume text extraction  
- **SpaCy, NLTK** – NLP processing  
- **Pandas** – Data manipulation  
- **Plotly Express** – Data visualization  
- **MySQL** – Database backend  

---

##  Installation & Setup

### 1. Clone the Repository
```bash
git clone git@github.com:Angell-14/HireScope.git

## Run Locally

Clone the project

```bash
  git clone git@github.com:Angell-14/HireScope.git
```

Go to the project directory

```bash
  cd HireScope
```

Create Virtual Environment

```
  python -m venv venv
```
Activate
```
  venv\Scripts\activate
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Create DB
```
    mysql -u your_username -p
    CREATE DATABASE resumedb;
```

Update username and password in __init__.py

Start the app
```bash
  streamlit run main.py
```

## Usage

1. **User Mode:** Upload your resume to receive smart recommendations, skill insights, and a score.
2. **Admin Mode:** Admins can log in to access a dashboard displaying user data and insights based on the collected data.


