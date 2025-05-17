
# Resume SkillMatch Analyzer

An AI-powered Resume Analyzer that matches your resume with a job description to provide a match score, identify relevant skills, and suggest improvements to enhance job-fit.

## 🔍 Project Overview

This project uses Natural Language Processing (NLP) to extract and compare skills from a user's resume and a provided job description. It highlights:

- Resume-to-job skill matching
- Match percentage calculation
- Suggested missing skills
- Visual analytics (pie, bar, venn diagrams)

---

## 📁 Folder Structure

```
resume_SkillMatch_Analyzer/
│
├── backend/
│   ├── analyze.py
│   ├── resume_parser.py
│   ├── skill_matcher.py
│   |── requirements.txt
│   
│
├── frontend/
│   ├── index.html
│   ├── js/app.js
│   ├── css/styles.css
│   |──images
│
├── .gitignore
├── README.md
└──
```

---

## 🚀 Features

- ✅ Upload resume and job description (PDF, DOCX, or TXT)
- ✅ NLP-based skill extraction and matching
- ✅ Match score breakdown (skill coverage + text similarity)
- ✅ Visual skill overview: Pie chart, Bar graph, Venn diagram
- ✅ Smart suggestions for missing skills

---

## 🛠️ Tech Stack

**Frontend:**
- HTML5, CSS3, JavaScript
- Chart.js for graphs
- File input UI and toggleable views

**Backend:**
- Python 3.10+
- Flask for API routing
- `python-docx`, `PyMuPDF` for file parsing
- `sklearn`, `nltk`, `spacy` for NLP

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/resume_SkillMatch_Analyzer.git
cd resume_SkillMatch_Analyzer
```

---

### 2. Backend Setup

> 🐍 Make sure you have Python 3.10+ installed

```bash
cd backend
python -m venv venv             # Create virtual environment
venv\Scripts\activate           # Activate it on Windows
pip install -r requirements.txt # Install dependencies
python analyze.py               # Start the Flask server
```

📍 Server will start at:  
**http://127.0.0.1:5000/**

---

### 3. Frontend Setup

> No build required — just open the file directly in a browser.

- Navigate to the `frontend` folder  
- Open `index.html` using any browser (Chrome, Edge, etc.)  
- Ensure your Flask backend is running in the background

---



## 🧪 Sample Use Case

1. Upload resume (`.pdf`, `.docx`, `.txt`)
2. Upload job description
3. Click "Analyze"
4. View:
   - Matching Score
   - Matching Skills
   - Missing Skills
   - Visual Skill Charts

---



## 💡 Future Improvements

- 📄 **Download optimized resume** based on suggested skills
- 🔐 Add user authentication and resume/job history
- 📤 Export improved resume in `.pdf` format
- 🤖 Integrate transformer models like BERT for better semantic matching
- 🚀 Deploy full-stack version using Render, Heroku, or Vercel
- 🌐 Add browser drag-and-drop file uploads and mobile responsiveness
- 🧩 Add multilingual support for resume/job description parsing

---

## 🙋‍♂️ Author

**Alamanda Hima Naga Rajasekhar**  
M.S. in Computer & Information Sciences  
Southern Arkansas University

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
