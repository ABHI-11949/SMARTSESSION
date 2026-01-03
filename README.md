# SMARTSESSION
\## Student Engagement \& Proctoring System



\### Tech Stack

\- Frontend: HTML + JavaScript

\- Backend: FastAPI (Python)

\- AI: MediaPipe + OpenCV

\- Real-time: WebSockets



\### Project Overview

This system monitors student engagement during online sessions.

It detects whether the student is focused, confused, or requires proctor attention.



\### Confusion Detection Logic

Instead of using generic emotion labels, confusion is detected using:

\- Eyebrow contraction (brow furrow)

\- Absence of smile

This logic is based on facial landmarks provided by MediaPipe.



\### Features

\- Real-time webcam monitoring

\- Proctor alerts for no face / multiple faces

\- Live student status dashboard for teachers



\### How to Run

1\. Install dependencies:

&nbsp;  pip install -r backend/requirements.txt



2\. Start backend server:

&nbsp;  uvicorn main:app --reload



3\. Open teacher dashboard:

&nbsp;  frontend/teacher/index.html



