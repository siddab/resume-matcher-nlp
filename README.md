NLP Resume Matcher & Feedback Tool

This project is part of our group assignment for NLP. It focuses on analyzing resumes and matching them to a given job description using Natural Language Processing techniques. It also gives simple feedback on writing style based on verbs and passive voice usage.

**What It Does**

Extracts resume content from PDF, DOCX, and TXT files

Analyzes sentence structure to spot passive voice and weak verbs

Matches resumes to a job description using semantic similarity

Ranks candidates and visualizes results in a chart

**Why We Built This**

Recruiters spend a lot of time screening resumes. We wanted to automate part of that process using NLP. Our tool helps shortlist resumes that are most relevant to a job and gives feedback on writing quality.

**Tech Stack**

Python 

spaCy – NLP and POS tagging

pdfplumber – Extracts text from PDFs

python-docx – Reads DOCX files

Sentence Transformers – For semantic embedding

scikit-learn – Cosine similarity

Matplotlib & Seaborn – For data visualization

**How It Works**

Resume Extraction

Reads text from resumes using appropriate libraries based on file type.

Linguistic Feedback

Uses spaCy to find weak verbs (like “worked”, “helped”) and checks for passive voice (e.g., “was managed”).

Semantic Matching

We used Sentence-BERT to convert resumes and job descriptions into vectors and calculated cosine similarity.

Ranking & Visualization

Top resumes are ranked and visualized using a bar chart showing similarity scores.


**Files**
NLP_Group_Assignment_Assignment_.ipynb – Main code 

README.md – You’re reading it!

Weak_verb.txt – (Optional) List of Python packages if needed
