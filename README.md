# Project_MyBookHub

Project: “MyBookHub” – Personal Book Collection Tracker
Project Goal
Build a full-stack web application where users can:

Register and log in.

Add, edit, and delete books in their personal collection.

Mark books as read/unread.

Add reviews or notes.

See statistics (e.g., how many books read per year, genre breakdown).

Tech Stack
Frontend:

React + Vite

Tailwind CSS

Axios

Backend:

Django + Django REST Framework

PostgreSQL

Optional:

Authentication via JWT

Docker for local setup

Core Features
User registration and login

CRUD operations for books (title, author, genre, read/unread, notes)

Tagging system or genre filtering

Statistics dashboard

Responsive design

Schedule Plan (4 Weeks)
Week 1 – Setup + Backend Development
Goal: Set up project structure and backend API

Tasks:

 Initialize Django project and app

 Set up PostgreSQL and environment variables

 Create models: User, Book

 Set up Django REST Framework

 Implement user authentication (JWT or DRF auth)

 Create API endpoints (register, login, list/add/edit/delete books)

 Test endpoints with Postman

Deliverables:

Working API with authentication and CRUD for books

Week 2 – Frontend Development
Goal: Build and connect the React frontend

Tasks:

 Set up React project with Vite and Tailwind

 Create login and register pages

 Create dashboard page (book list + add/edit form)

 Integrate API using Axios

 Implement routing (React Router)

Deliverables:

User can log in, view, add, and update books

Week 3 – Extra Features + Statistics
Goal: Add user-friendly features and insights

Tasks:

 Add genre filtering

 Add read/unread toggle

 Create statistics view (charts with Chart.js or Recharts)

 Add book notes and sorting

Deliverables:

Enhanced frontend with filtering and stats

Week 4 – Testing, Deployment, and Polish
Goal: Make the app stable, good-looking, and deployable

Tasks:

 Add form validation

 Write unit tests (backend and frontend)

 Polish UI with Tailwind

 Deploy backend (Render or Railway) and frontend (Netlify or Vercel)

Deliverables:

Fully working, deployed app you can show in your portfolio

Stretch Goals (Optional)
Google Books API integration (auto-fill book data)

Book cover upload (with Cloudinary)

Dockerize frontend and backend

Mobile-first responsive design

