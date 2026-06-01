# Murshid

Murshid is a smart academic advising web system. It helps students ask questions about their study plan and academic regulations through one chatbot interface.

The system includes:
- Study Plan Agent
- Knowledge Base Agent
- Chatbot Layer
- React Frontend

## Technologies

Backend:
- Python
- Flask
- Firebase Firestore
- OpenAI
- ChromaDB

Frontend:
- React
- TypeScript
- Vite
- Firebase SDK

## Backend Setup

1. Open the backend folder:

cd murshid_study_plan_agent


2. Create virtual environment:

python -m venv venv


3. Activate virtual environment:

venv\Scripts\activate


4. Install requirements:

pip install -r requirements.txt



5. Make sure Firebase service account file is added and configured in:

firebase/firebase_config.py


6. Make sure the Knowledge Base dataset exists in:


knowledge_base/data/knowledge_base_dataset_ready.xlsx


7. Run backend:


python app.py


Backend runs on:


http://127.0.0.1:5000


## Frontend Setup

1. Open the frontend folder:


cd murshid-frontend

2. Install packages:

npm install


3. Run frontend:

npm run dev


Frontend runs on:


http://localhost:5173

## How to Use

1. Open the frontend URL.
2. Login using an existing student ID from Firestore.
3. Start asking questions in the chatbot.

Example questions:


هل أقدر أسجل CS2105؟
ما هو تعريف العام الدراسي؟
اقترح لي 5 مواد للفصل القادم




