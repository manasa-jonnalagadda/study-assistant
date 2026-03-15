# Smart Study Assistant 🎓

An AI-powered web application that helps students study smarter by generating summaries, flashcards, and quizzes from their notes or uploaded files.

## Live Demo
🔗 [Coming soon after deployment]

## Features
- 📝 **Smart Summary** — Paste notes or upload a file and get a clean AI-generated summary
- 🃏 **Flashcard Generator** — Automatically creates Q&A flashcards with flip animation
- 📊 **Interactive Quiz** — Generates multiple choice questions with instant answer feedback
- 📁 **File Upload Support** — Supports PDF, Word (.docx), PowerPoint (.pptx), Excel (.xlsx), and TXT files
- 🎯 **Custom Count** — Choose how many flashcards or quiz questions to generate (3–15)
- 🌙 **Dark Mode UI** — Modern glassmorphism design with animated gradient background

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| AI | Google Gemini 2.5 Flash API |
| Frontend | HTML, CSS, JavaScript |
| File Parsing | PyPDF2, python-docx, python-pptx, openpyxl |
| Environment | python-dotenv |
| Deployment | Render.com |

## Project Structure
```
study-assistant/
│
├── app.py              # Flask backend & API routes
├── requirements.txt    # Python dependencies
├── .env                # API key (not uploaded to GitHub)
├── .gitignore          # Files excluded from GitHub
│
└── templates/
    └── index.html      # Frontend UI
```

## How It Works
1. User pastes notes or uploads a file (PDF, Word, etc.)
2. Flask receives the content and sends it to Gemini AI API
3. Gemini processes the content based on selected mode
4. Results are displayed as summary, flashcards, or interactive quiz

## Getting Started

### Prerequisites
- Python 3.11+
- Google Gemini API key (free at aistudio.google.com)

### Installation

1. Clone the repository
```bash
git clone https://github.com/manasa-jonnalagadda/study-assistant.git
cd study-assistant
```

2. Create virtual environment
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Create `.env` file and add your API key
```
GEMINI_API_KEY=your_gemini_api_key_here
```

5. Run the app
```bash
python app.py
```

6. Open your browser and go to `http://127.0.0.1:5000`

## What I Learned
- Building REST APIs with Flask
- Integrating Google Gemini LLM API
- Prompt engineering for structured AI outputs
- Parsing multiple file formats in Python
- Frontend development with HTML, CSS, JavaScript
- Secure API key management with environment variables
- Version control with Git and GitHub

## Author
**Lakshmi Manasa Jonnalagadda**  
B.Tech Computer Science (AI & ML) — SRM University AP  
📧 manasajonnalagadda10@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/manasa-jonnalagadda)  
🐙 [GitHub](https://github.com/manasa-jonnalagadda)
