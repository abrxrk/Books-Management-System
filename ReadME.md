# FastAPI Books Project 📚

This project is part of the [FastAPI - The Complete Course](https://www.udemy.com/course/fastapi-the-complete-course/) on Udemy. It focuses on building a basic REST API using FastAPI to manage a collection of books.

## 🚀 Overview

The project covers:
- Setting up FastAPI
- Creating GET and POST endpoints
- Working with path and query parameters
- Building and validating data models using Pydantic

---

## 🧰 Tech Stack

- **FastAPI** – High-performance web framework for APIs
- **Uvicorn** – ASGI server for running FastAPI apps
- **Python 3.10+**
- **Pydantic** – Data validation and parsing

---

## 📁 Project Structure

books_project/
├── main.py # Main FastAPI app
├── models.py # Pydantic models (Book schema)
├── database.py # Temporary in-memory storage
├── requirements.txt # Project dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🔧 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fastapi-books-project.git
cd fastapi-books-project
2. Create a Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the FastAPI Server
bash
Copy
Edit
uvicorn main:app --reload
Visit the interactive Swagger UI at: http://127.0.0.1:8000/docs

📬 API Endpoints
Method	Endpoint	Description
GET	/books	Retrieve all books
GET	/books/{book_id}	Retrieve a book by ID
POST	/books	Add a new book
GET	/books/search?author=	Filter books by author

🧑‍🎓 Learning Progress
This project is being developed step-by-step following:

✅ GET Request Basics

✅ Path and Query Parameters

✅ POST Request Method

⏳ Upcoming: PUT, DELETE, and DB integration

🧑‍💻 Author
Abrar Ateeq
GitHub: @abrxrk

