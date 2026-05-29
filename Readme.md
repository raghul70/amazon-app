🛒 Amazon App (Frontend)

📌 Project Overview
This is a simple frontend clone of an Amazon-like shopping website built using HTML, CSS, and JavaScript. It includes basic UI pages like home, login, product listing, and static assets.

🚀 How to Run the Project
🔹 Method 1: Open directly in browser
Download or clone the project

Open the folder:

amazon-app
# Backend Setup Instructions

## Prerequisites

Make sure the following are installed:

* Python 3.10+
* Git
* pip
* Virtual Environment support

---

## Clone Repository

```bash
git clone <repository_url>
```

```bash
cd project_name
```

---

## Create Virtual Environment

### Linux / macOS

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

### Windows

```bash
python -m venv venv
```

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the root directory.

Example:

```env
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
```

---

## Run FastAPI Server

```bash
uvicorn app.main:app --reload
```

Server runs at:

```text
http://127.0.0.1:8000
```

---

## API Documentation

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

Scalar API:

```text
http://127.0.0.1:8000/scalar
```

---

## Project Structure

```text
project/

├── app/
├── templates/
├── static/
├── uploads/
├── requirements.txt
├── .env
└── README.md
```

---

## Common Commands

### Create New Branch

```bash
git checkout -b branch_name
```

### Pull Latest Changes

```bash
git pull origin main
```

### Push Branch

```bash
git push -u origin branch_name
```

Double click on:

index.html
It will open in your default browser
🔹 Method 2: Using VS Code (Recommended)
Open project in VS Code
Install extension: Live Server
Right-click index.html

Click:

Open with Live Server

The project will run at:

http://127.0.0.1:5500/
📁 Project Structure
amazon-app/
│
├── index.html
├── templates/
│   ├── login.html
│   ├── signup.html
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│
└── README.md
🛠️ Technologies Used
HTML5
CSS3
JavaScript (Vanilla JS)
Bootstrap (optional if used)

🎯 Features
Responsive homepage design
Login & Signup UI
Product listing layout
Navigation bar
Static image assets

⚠️ Notes
This is a frontend-only project
No backend or database is connected
All data is static/dummy
📌 Future Improvements
Add backend (Node.js / Spring Boot / Django)
Add authentication system
Connect to database
Add cart & payment functionality