Poll App
A simple web application built with Django to create and manage polls, allowing users to vote and view results.

Features
Create Polls: Add new polls with a question and multiple choices.
Vote on Polls: Users can select a choice and submit their votes.
View Results: See live poll results with vote counts for each option.
Responsive Design: User-friendly interface that works across devices.

Prerequisites
Before running the application, ensure the following are installed:

Python (>=3.8)
Django (>=4.0)
SQLite (default database used in development)

Installation
Clone the Repository
git clone https://github.com/yourusername/poll-app.git
cd poll-app

Set Up Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies
pip install -r requirements.txt

Apply Migrations
python manage.py migrate

Run the Server
python manage.py runserver
