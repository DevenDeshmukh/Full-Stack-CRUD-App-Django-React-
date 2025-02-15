<h1>Full-Stack CRUD App (Django & React)</h1>

**📌 Project Overview**

This is a full-stack CRUD (Create, Read, Update, Delete) application built using Django REST Framework for the backend and React.js for the frontend. The app allows users to manage a collection of books, performing operations such as adding, updating, viewing, and deleting books.

**📜 Description**

This project demonstrates how to build a full-stack web application with Django and React. The backend API is developed using Django REST Framework (DRF), providing endpoints for managing books, while the frontend is built with React to create an interactive user experience. The application supports essential CRUD operations and ensures seamless communication between the frontend and backend using fetch API requests.

**🚀 Technologies Used**

Backend (Django & DRF)

Django

Django REST Framework

SQLite (Default Database)

CORS Headers

Frontend (React.js)

React.js

Fetch API

useState & useEffect Hooks

CSS for Styling

🔧 Features

📖 Add Books (Title & Release Year)

✏️ Update Book Title

🗑️ Delete Books

📜 View Books (Fetched from Django API)

🌐 API Integration using Fetch

**🛠️ Setup Instructions**

1️⃣ Clone the Repository
```
git clone https://github.com/your-username/crud-django-react.git
cd crud-django-react
```
Extract the zip file named "react-django"

2️⃣ Backend Setup (Django)
```
  cd backend
  python3 -m venv venv
  source venv/bin/activate  # For Mac/Linux
  venv\Scripts\activate  # For Windows
  pip install -r requirements.txt
  python manage.py migrate
  python manage.py runserver
```

3️⃣ Frontend Setup (React)
  ```
  cd frontend
  npm install
  npm start
```

**📡 API Endpoints**
GET - /api/books/- Fetch all books
POST- /api/books/create/- Add a new book
PUT-/api/books/{id}/-Update a book title
DELETE-/api/books/{id}/-Delete a book

**📷 Screenshots**
<img width="1440" alt="Screenshot 2025-02-15 at 9 55 46 AM" src="https://github.com/user-attachments/assets/5965fbca-2d7f-4809-8a54-513440e9d86f" />
<img width="1440" alt="Screenshot 2025-02-15 at 9 55 16 AM" src="https://github.com/user-attachments/assets/915e0910-37c1-4ffe-bd06-189e533d3697" />
<img width="1440" alt="Screenshot 2025-02-15 at 9 55 02 AM" src="https://github.com/user-attachments/assets/97c20cd8-1a52-424b-9eda-7ed4e4ecaff4" />
<img width="1440" alt="Screenshot 2025-02-15 at 9 54 13 AM" src="https://github.com/user-attachments/assets/7a46cd91-0eb7-4749-8d30-87ff2e5203c0" />

