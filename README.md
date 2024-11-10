# Task Management Application

This is a task management application that allows users to register, log in, manage tasks, set reminders, and tag other users. It includes functionalities for task creation, editing, deletion, completion status management, filtering tasks, and sending email notifications.
![image](https://github.com/user-attachments/assets/d3ebd2a8-b827-4ca7-bdb7-98d37da242a5)
![image](https://github.com/user-attachments/assets/3e572887-1755-4827-9f27-aefd9f1eb370)
![image](https://github.com/user-attachments/assets/f5bbf2b6-a417-4900-ba85-48349c320503)


## Features

- **User Registration and Login**
  - Users can create an account (register).
  - Users can log in to the application using their credentials.

- **Authentication**
  - The application uses JWT (JSON Web Tokens) for user authentication.

- **CRUD Operations for Tasks**
  - Users can create, edit, delete, and list tasks.
  - Each task has attributes such as `title`, `description`, `deadline`, and `status`.

- **Task Completion Status**
  - Users can mark tasks as complete or incomplete.
  - Filter tasks based on their completion status (complete or incomplete).

- **Reminder for Tasks Near Deadline**
  - Tasks can have a reminder that triggers when the task is nearing its deadline.
  - Push notifications are sent via email when the reminder is triggered.

- **Tagging Other Users**
  - Users can tag other users in a task by their email or username.
  - When tagged, users will receive a push notification via email.


## Setup and Installation
1. **Clone the repository**:
```bash
git clone https://github.com/phananhlocpal/task-mana
cd task-mana
```
2. **Update Database**
After cloning the repository, open the backend folder and update the database schema using the Package Manager Console:
```bash
Update-Database
```
This command will apply any pending migrations to the database.
4. **Run the backend**
In the backend folder, run the application using the following command:
```bash
dotnet run
```
5. **Run the Frontend**
In the frontend folder, install the required npm packages and start the Angular application:
```bash
npm start 
```
