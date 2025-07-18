
# 🧠 Resume AI – An AI-Powered Resume Analyzer and Builder

Resume AI is an intelligent, web-based application designed to help users **build, optimize, and analyze** resumes using Artificial Intelligence. Built using Python, Streamlit, and advanced NLP techniques, the tool provides ATS compatibility analysis, keyword and skill gap detection, and job-role-specific recommendations to improve the effectiveness of resumes in real-world job markets.

---

## 🌐 Preview

![Preview](assets/preview-black.png) <!-- Add your preview screenshot later -->

---

## 🎯 Objectives

- Create professional and ATS-friendly resumes
- Detect keyword and skill gaps using AI/NLP
- Offer real-time feedback on formatting and structure
- Provide customizable templates for resume building
- Analyze resumes across multiple formats (PDF, DOCX, XLSX)
- Recommend job roles, trending skills, and relevant resources

---

## ⚙️ Tech Stack

| Component       | Technology Used                              |
|----------------|-----------------------------------------------|
| Frontend        | Streamlit, HTML, CSS                         |
| Backend         | Python                                       |
| Database        | SQLite3                                      |
| AI/NLP          | spaCy, NLTK, scikit-learn                    |
| File Handling   | PyPDF2, python-docx, openpyxl                |
| Visualization   | Plotly                                       |
| Deployment      | Localhost, Streamlit Cloud, Docker           |

---

## 💡 Core Modules

- **Resume Analyzer** – Checks for ATS compatibility, keyword and skill gaps
- **Resume Builder** – Offers four smart templates with custom form inputs
- **AI Optimization Engine** – Suggests improvements based on job roles
- **Dashboard** – Visualizes scores and analysis results
- **Job Matching** – Recommends career paths and skill enhancement
- **Export System** – Supports PDF and DOCX download
- **Admin Panel** – Controls templates, users, and feedback analytics

---

## 📂 Folder Structure

```

Resume-AI/
├── assets/                  # Logos, preview images
├── data/                    # Sample resumes / job descriptions
├── modules/                 # NLP and AI logic
├── utils/                   # Helper functions
├── templates/               # Resume HTML templates
├── app.py                   # Main Streamlit app
├── requirements.txt         # Dependencies
├── Dockerfile               # Docker configuration
├── README.md                # This file

````

---

## 🖥️ Installation Guide

### 🔸 Local Setup

```bash
git clone https://github.com/your-username/Resume-AI.git
cd Resume-AI

# (Optional) Create a virtual environment
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
````

### ☁️ Streamlit Cloud Deployment

1. Push your code to a public GitHub repository
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Connect your repo and deploy the app
4. Set `app.py` as the main file path

> Ensure you include:
>
> * `requirements.txt`
> * `packages.txt` with `chromium`, `chromium-driver`, `xvfb`, etc.

---

## 🚧 Limitations

* Supports only English resumes
* Limited customization in visual design templates
* Doesn't integrate with live job portals (yet)
* ATS analysis based on general models, not company-specific
* No interview prep or Q\&A generation (future scope)

---

## 🔭 Future Scope

* REST API for external integrations
* Advanced AI models (LLMs) for deeper insights
* Real-time job search via LinkedIn/Indeed integration
* Multi-language support
* Enhanced UI using React or Angular
* Role-specific customization of resume analysis
* Secure encrypted cloud-based resume storage


## 👤 Author

**Ravi M Shetty**
📌 SDM Degree College, Honnavar
🌐 [Portfolio](https://ravishetty-portfolio.netlify.app)
🔗 [LinkedIn](https://www.linkedin.com/in/ravi-m-shetty/)
💻 [GitHub](https://github.com/Ravishetty07)


> “A well-crafted resume is your passport to opportunity. Resume AI helps you build it smarter.” 💼✨



