# PowerPoint Generator API 🚀
By Simra kazmi | BCA 2nd Year

A Flask REST API that generates PowerPoint (PPTX) from JSON data using python-pptx.

### Features
- POST /generate -> Creates PPT with title + slides
- Auto title slide + content slides
- Downloadable .pptx file

### Tech Stack
Python, Flask, python-pptx

### How to Run Locally
pip install -r requirements.txt
python app.py

### Example API Request
POST /generate
{
  "title": "AI Presentation",
  "slides": ["What is AI?", "Uses of AI"]
}

### My Links
GitHub: simrahashmi5-debug
