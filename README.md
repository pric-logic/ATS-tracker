
# ATS Tracker: AI-Powered Resume Analyzer

ATS Tracker is a Streamlit web application that leverages **Google Gemini AI** and Retrieval-Augmented Generation (RAG) to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). This tool analyzes your resume against a job description, identifies missing keywords, provides a match percentage, and generates a tailored professional summary—all in seconds.

---

## Features

- **Resume Parsing:** Upload your resume (PDF/Word). The app extracts and processes the content for analysis.
- **Job Description Analysis:** Paste any job description. The app compares your resume to the JD for alignment.
- **AI-Powered Insights:** Uses Gemini AI and RAG to:
  - Calculate a **match percentage** between your resume and the job description.
  - Identify **missing keywords** crucial for ATS optimization.
  - Generate a **custom profile summary** tailored to the job requirements.
  - Provide actionable feedback for resume improvement.
- **User-Friendly Interface:** Built with Streamlit for an interactive, intuitive experience.
- **ATS Compatibility Check:** Ensures your resume meets common ATS formatting and content standards.

---

## How It Works

1. **Input Job Description:** Paste the job description for your target role.
2. **Upload Resume:** Upload your resume as a PDF or Word document.
3. **AI Analysis:** The app uses Gemini AI and RAG to analyze, compare, and generate insights.
4. **Results:** Instantly receive:
   - Match percentage
   - List of missing keywords
   - Tailored profile summary
   - Suggestions for improvement

---

## Technologies Used

| Technology             | Purpose                                        |
|------------------------|------------------------------------------------|
| **Streamlit**          | Web application interface                      |
| **Google Gemini AI**   | Resume and JD analysis, summary generation     |
| **RAG**                | Enhanced context-aware responses               |
| **Python**             | Backend logic                                  |
| **PDF/Docx Libraries** | Resume parsing and text extraction             |

---

## Installation

```
git clone https://github.com/yourusername/ats-tracker.git
cd ats-tracker
pip install -r requirements.txt
# Ensure Poppler is installed and added to PATH for PDF processing
streamlit run app.py
```

---

## Usage

1. Launch the app with `streamlit run app.py`.
2. Paste your job description into the provided text area.
3. Upload your resume file.
4. Review the AI-generated analysis and suggestions.

---

## Example Output

> **Match Percentage:** 78%  
> **Missing Keywords:** Python, Data Visualization, Machine Learning  
> **Profile Summary:**  
> "Experienced data analyst with expertise in data processing and reporting, seeking to leverage advanced analytics skills for [Job Title] at [Company]."

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests for enhancements and bug fixes.

---

## License

MIT License

---

## Acknowledgements

- Inspired by the need to make job applications smarter and more effective for everyone.
- Built with guidance from the Streamlit and AI developer community.

---

**Empower your job search with AI. Optimize your resume. Land your dream job!**
