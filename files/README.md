# README.md
# AutoUI Wireframe Generator

AutoUI is an AI-powered system that converts rough UI ideas and user preferences
into structured, low-fidelity wireframes. It is designed as a final-year project
and can be extended into a startup-ready product.

## Features
- Text-to-wireframe generation
- Preference-based UI customization
- Clean component hierarchy
- Web-based preview

## Tech Stack
- Frontend: React + Vite + Tailwind CSS
- Backend: FastAPI (Python)

## How to Run

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
