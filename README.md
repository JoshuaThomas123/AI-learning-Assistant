AI Learning Assistant
An AI-powered, full-stack web application that helps students study more effectively by automatically generating personalised learning materials from uploaded documents.

What It Does
Upload any educational PDF and the application will instantly generate:
Summaries: breakdowns of key content
Flashcards: question and answer pairs for active recall
Mind Maps:  creates a list of key concept nodes to help structure your understanding
Quiz Questions: auto-generated questions to test understanding

Tech Stack
Frontend:	React.js, React Router
Backend:	Flask (Python)
AI / NLP:	Hugging Face Transformers, LLMs
Database:	SQLAlchemy
Other	RESTful APIs, PDF processing (pdfplumber)


Prerequisites
Python installed globally
npm installed
Backend Setup
bash
pip install flaskpip install pdfplumberpip install flask-corspip install flask-sqlalchemypip install torchpip install transformers
Then run the backend


Frontend Setup
cd frontend npm install, npm install react-router-dom, npm run start
Important: Start the backend before the frontend.
Project Highlights
Integrates Hugging Face ML models to analyse text and extract key concepts
RESTful API architecture connecting frontend and backend
Modular design with test-driven development (TDD) principles
Clean, interactive UI for dynamic engagement with AI-generated content
