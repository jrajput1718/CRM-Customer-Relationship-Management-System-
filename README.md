# CRM-Customer-Relationship-Management-System-
This project is a Customer Relationship Management (CRM) system built with HTML,css for the frontend and Python Django for the backend.
Overview
This CRM project aims to streamline customer management processes for businesses. It provides essential features such as user authentication, customer management, contact management, task management, and an analytics dashboard.

Features
User Authentication: Sign up, log in, and manage user accounts securely.
Customer Management: Add, edit, and delete customer records.
Contact Management: Keep track of customer contacts and interactions.
Task Management: Assign tasks to team members and track progress.
Analytics Dashboard: Visualize customer data and track key metrics.
Technologies Used
Frontend
HTML
CSS
Backend
Python
Django
Django REST Framework (for building RESTful APIs)
Django ORM (for database interactions)
MySQL DB
Getting Started
To get started with the project:

Clone the repository: git clone https://github.com/jrajput1718/CRM-Customer-Relationship-Management-System-.git
Install frontend dependencies: cd crm-project/frontend && npm install
Install backend dependencies: cd ../backend && pip install -r requirements.txt
Configure the backend by creating a .env file in the backend directory with necessary environment variables.
Run migrations to create database tables: python manage.py migrate
Start the backend server: python manage.py runserver
Start the frontend development server: cd ../frontend && npm start
Open your browser and navigate to http://localhost:3000 to view the application.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow the standard GitHub flow:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Create a new Pull Request.
