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
