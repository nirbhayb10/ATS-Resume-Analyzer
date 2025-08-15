📄 Smart ATS Resume Analyzer

An AI-powered tool that helps job seekers optimize their resumes for Applicant Tracking Systems (ATS).
With just a job description and a PDF version of your resume, the app evaluates the match, identifies missing keywords, and provides actionable improvement suggestions — all in real time.

🚀 Features

AI-Powered Analysis – Uses Google’s Gemini model to intelligently compare your resume against a given job description.

Keyword Gap Detection – Identifies important skills and keywords missing from your resume.

Match Score – Gives a clear percentage score showing how well your resume fits the role.

Interactive Web App – Simple, clean UI built with Streamlit for easy resume uploads and instant feedback.

PDF Support – Extracts text directly from PDF resumes for accurate processing.

🛠️ Tech Stack

Frontend & UI: Streamlit

Backend Processing: Python, FastAPI

AI Model: Google Generative AI (Gemini)

PDF Parsing: PyPDF2

Environment Management: python-dotenv

📦 Installation

Clone the repository

git clone https://github.com/your-username/smart-ats-analyzer.git
cd smart-ats-analyzer


Install dependencies

pip install -r requirements.txt


Set up API key
Create a .env file in the project root and add your Google API key:

GOOGLE_API_KEY=your_api_key_here


Run the application

streamlit run app.py

📋 How to Use

Paste the full job description into the text area.

Upload your resume as a PDF.

Click Analyze Resume.

View your match score, missing keywords, and a summary with suggestions.

💡 Example Output

Match Score: 78%

Missing Keywords: ["Docker", "Kubernetes", "CI/CD"]

Profile Summary: Detailed feedback on strengths, weaknesses, and suggestions for improvement.

🤝 Contributing

Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

📜 License

This project is licensed under the MIT License — see the LICENSE file for details.
