
# AI Fact Video Generator

## Setup Backend
cd backend
pip install -r requirements.txt
cp .env.example .env # Keys eintragen!
uvicorn main:app --reload

## Setup Frontend
cd frontend
npm install
npm run dev

## Zugriff
Frontend: http://localhost:3000
Backend:  http://localhost:8000
