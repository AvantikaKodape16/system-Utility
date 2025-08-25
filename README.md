# System Utility Fullstack Project

## 1. Backend (FastAPI + SQLite)
```sh
cd backend
pip install fastapi uvicorn pydantic
python -m uvicorn app.main:app --reload
```

## 2. Frontend (React)
```sh
cd frontend
npm install
npm install serve
npm run build
npm start
```
Dashboard will be at http://localhost:3000 if you use create-react-app, or http://localhost:5000 if you use `serve`.

## 3. Client Utility
```sh
cd client
pip install requests
python main.py
```

## Notes
- You may need to adjust/expand system checks for your OS.
- For Windows/Mac/Linux, some checks require admin privileges.
- For production, secure the API and use HTTPS.
