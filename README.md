# ATS Resume Expert

An AI-powered **Applicant Tracking System (ATS)** Resume Analyzer built with **Streamlit** and Google Gemini API.

---

## Features

- Upload your resume as a PDF.
- Input a job description text.
- Get a professional evaluation of how well the resume matches the job description.
- Receive feedback highlighting strengths, weaknesses, keyword matches, and match percentage.

---

## Tech Stack

- Python 3.x
- Streamlit for web interface
- pdf2image for PDF to image conversion
- Google Generative AI Gemini API for resume analysis
- python-dotenv for environment variable management
- Pillow for image processing

---

## Setup & Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Pavithri-Apeksha/ats-resume-expert.git
   cd ats-resume-expert
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate       # Linux/Mac
   venv\Scripts\activate          # Windows PowerShell
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Create a .env file in the root directory and add your Google API key:
   ```init
   GOOGLE_API_KEY=your_google_api_key_here
5. Run the Streamlit app:
   ```bash
   streamlit run app.py

## Usage
- Open the web app in your browser.
- Paste or type the job description.
- Upload your resume PDF.
- Click on "Tell Me About the Resume" to get a detailed analysis.
- Or click "Percentage match" to get how well the resume matches the job description.
