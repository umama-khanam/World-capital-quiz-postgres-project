# World-capital-quiz-postgres-project
A web-based quiz game where a random country appears and you must enter its capital. Each correct answer increases your score; one wrong answer ends the game. Built using Node.js, Express.js, and PostgreSQL (pgAdmin) to manage and fetch country-capital data.
# 🌍 World Capital Quiz

A simple and interactive quiz web app where a random country appears, and the user must type in the correct capital. Each correct answer increases the score by 1. One incorrect answer ends the game and displays your final score.

> ⚠️ This project is backend-based using Node.js and Express, so it **does not have a live link**. Follow the steps below to run it locally.

---

## 🚀 Tech Stack Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL (pgAdmin)
- **Others**: pg module for connecting Node with PostgreSQL

---

## ✨ Features

- Random country shown on every refresh
- Submit answer to guess the capital
- Score increases with each correct answer
- Game ends on the first incorrect guess
- Final score display on game over
- Country-capital data stored and managed via PostgreSQL

---

## 📸 Screenshot

![World Capital Quiz Homepage Screenshot](https://github.com/umama-khanam/World-capital-quiz-postgres-project/blob/main/Screenshot%20(8103).png)

> Replace the image path if your screenshot is saved elsewhere

---

## 📚 What I Learned

- Setting up a PostgreSQL database with pgAdmin  
- Connecting PostgreSQL to a Node.js backend using the `pg` module  
- Creating RESTful endpoints using Express.js  
- Handling form data and game logic in JavaScript  
- Structuring a full-stack app without using frontend frameworks

---

## 🖥️ Run Locally

To run this project on your machine:

1. **Clone the repository**
    git clone https://github.com/your-username/world-capital-quiz.git
   cd world-capital-quiz
   Install dependencies
   npm install
Set up PostgreSQL database

Create a new database in pgAdmin

Import the provided .sql file to populate the country-capital table

Update the database credentials in your .env or config file

Run the server

node index.js
Open in browser
Go to http://localhost:3000 in your browser

## 👩‍💻 Made By
Umama Khanam
Passionate about building web apps and always eager to learn new technologies.
