# RetainSure-Assignment

This repository contains solutions to the two tasks assigned as part of the Retain coding challenge:

✅ **Task 1: User Management API Refactor**  
✅ **Task 2: URL Shortener Service**

---

## 📁 Repository Structure

retain-coding-challenge/
├── task1_user_management/
│ ├── app.py
│ ├── auth.py
│ ├── models.py
│ ├── database.py
│ ├── schemas.py
│ ├── requirements.txt
│ └── ...
├── task2_url_shortener/
│ ├── app.py
│ ├── models.py
│ ├── database.py
│ ├── requirements.txt
│ └── ...
└── README.md

yaml
Copy
Edit

---

## 📌 Task 1 – User Management API Refactor

A modernized FastAPI-based User Management API with:
- Modular file structure
- Secure password hashing (bcrypt)
- JWT-based authentication
- SQLAlchemy-based SQLite storage

### 🚀 How to Run Task 1

1. Navigate to the project folder:
    ```bash
    cd task1_user_management
    ```
2. (Recommended) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    venv\Scripts\activate     # Windows
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Start the FastAPI server:
    ```bash
    uvicorn app:app --reload
    ```
5. Visit the API documentation at: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## 📌 Task 2 – URL Shortener Service

A FastAPI-based URL shortener with:
- URL shortening & redirection
- Analytics tracking (visit counts)
- Input validation & error handling
- SQLAlchemy + SQLite for data persistence

### 🚀 How to Run Task 2

1. Navigate to the project folder:
    ```bash
    cd task2_url_shortener
    ```
2. (Recommended) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    venv\Scripts\activate     # Windows
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Start the FastAPI server:
    ```bash
    uvicorn app:app --reload
    ```
5. Visit the API documentation at: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## ✅ Features Covered

### Task 1
- User registration with password hashing
- User login with JWT issuance
- Token-based authentication
- Modularized Python code
- Security best practices

### Task 2
- Shorten long URLs with a unique code
- Redirect to original URL when visiting shortened code
- Track and store the number of visits
- Full CRUD-friendly model ready for extension

---

## 🧪 Testing

Both tasks include manually testable endpoints in FastAPI's auto-generated Swagger UI:
- Run the server (`uvicorn ...`)
- Go to `/docs`
- Interact with the API directly in your browser

---

## ⚙️ Requirements

- Python 3.8+
- pip

All other requirements are included in the respective `requirements.txt` files for each task.

---

## 📬 Contact

For any questions or clarifications, please reach out to me via GitHub issues or email.
Name : Challa Samatha,
Email : samathachowdary2004@gmail.com.

---
