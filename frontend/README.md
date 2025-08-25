🚀 Fullstack CRUD Application

This project is a Fullstack CRUD (Create, Read, Update, Delete) Application built using React.js for the frontend, Spring Boot for the backend, and MySQL as the database. It demonstrates a complete integration between a modern frontend framework and a robust backend API for managing persistent data.

📂 Project Structure:-

backend/ → Spring Boot application (REST APIs + database connection)
frontend/ → React application (user interface)

⚙️ Backend Setup (Spring Boot):-
Navigate to the backend folder.
Run the application with: mvn spring-boot:run
The backend will be available at http://localhost:8080
Ensure MySQL is running and application.properties has correct database credentials.

💻 Frontend Setup (React):-
Navigate to the frontend folder.
Install dependencies with: npm install
Start the frontend with: npm start
The React app will run on http://localhost:3000

🔗 API Integration:-
The React frontend communicates with the Spring Boot backend using REST APIs:
GET → Fetch records
POST → Add a new record
PUT → Update an existing record
DELETE → Remove a record

✨ Features
Add new entries
View all entries in a list or table format
Update existing entries
Delete entries
Frontend and backend fully connected with database

🚀 How to Run the Project
Open two terminals.
Terminal 1 (Backend): run mvn spring-boot:run from the backend folder.
Terminal 2 (Frontend): run npm start from the frontend folder.
Open your browser and visit http://localhost:3000 to use the application.

🛠️ Tech Stack:-
Frontend: React.js, Axios
Backend: Spring Boot, Maven
Database: MySQL
