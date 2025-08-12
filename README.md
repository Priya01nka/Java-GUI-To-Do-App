# Java-GUI-To-Do-App
This project is a full-stack To-Do List application built with Spring Boot for the backend and HTML, CSS, and JavaScript for the frontend. It allows users to create, view, update, and delete tasks through a simple and responsive web interface. Tasks are stored in an H2 in-memory database using Spring Data JPA and the app follows a RESTful API architecture.
Features
Add New Tasks – Users can enter a task name and add it to the list.
Mark Tasks as Done/Undo – Clicking the “Done” button toggles task completion (done or undone).
Delete Tasks – Users can remove tasks from the list permanently.
Persistent Storage – Tasks are saved in the H2 database and remain available until the application restarts.
Responsive Design – The frontend is styled with CSS to be clean and mobile-friendly.
REST API –
GET /api/tasks – Retrieve all tasks.
POST /api/tasks – Add a new task.
PUT /api/tasks/{id} – Toggle completion status.
DELETE /api/tasks/{id} – Delete a task.
H2 Console – Web-based UI to view database tables (/h2-console).

Technologies Used

Backend

Spring Boot – Framework for creating the backend API.
Spring Web – For building RESTful web services.
Spring Data JPA – For database operations.
H2 Database – In-memory database for development/testing.

Frontend

HTML5 – Structure of the web page.
CSS3 – Styling and responsive layout (external style.css).

JavaScript (Fetch API) – Asynchronous requests to backend APIs
