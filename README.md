# Simple Task Management System

## Overview
The **Simple Task Management System** is a web-based application that helps users manage their tasks efficiently. Users can create, view, edit, delete, and prioritize tasks. The system also includes user authentication, task assignment, and a color-coded priority management system

---

## Features

### 1. **Task Creation**
- A user-friendly form to create tasks.
- Each task includes a title, description, due date, and priority assignment.
- Tasks are automatically added to their respective priority lists.

### 2. **Task List**
- Displays all tasks with pagination for better organization and performance.
- Task details include the title, due date, and status (e.g., "pending," "completed").
- Data is fetched and updated dynamically using AJAX.

### 3. **Task Details**
- A dedicated page to view detailed information about a specific task.
- Displays the task description, due date, and priority.

### 4. **Task Editing**
- Users can edit task details, including the title, description, due date, and priority.
- Changes are saved dynamically and reflected immediately.

### 5. **Task Deletion**
- Option to delete a task with a confirmation dialog to prevent accidental deletions.

### 6. **Task Status Update**
- Users can update a task's status (e.g., "pending" → "completed" or vice versa).

### 7. **User Authentication**
- A secure user authentication system ensures only authorized users can access the system.
- Features include:
  - User login and logout.
  - Assigned task visibility: users can only see their assigned tasks.
  - Admin functionality to add/remove users and assign tasks.

### 8. **Priority Management**
- Tasks can be moved between priority lists.
- Priority categories are color-coded for quick identification.

### 9. **Visual Representation**
- Priority lists are visually distinct using colors to enhance user experience and organization.

---

## Technologies Used
- **Frontend**: React.js, Bootstrap, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT-based authentication
- **Tools**: Fetch API, AJAX for dynamic data handling

---

## Installation

### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB server (local or cloud).

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/simple-task-management-system.git
   cd simple-task-management-system
   backend api - https://simple-task-management-system.onrender.com
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root directory and add the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Start the application:**
   ```bash
   npm start
   ```

5. **Run the frontend:**
   - Navigate to the `client` folder and install dependencies:
     ```bash
     cd client
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

---

## API Endpoints

### Authentication
- `POST /api/auth/login`: User login.
- `POST /api/auth/register`: Register a new user.

### Tasks
- `GET /api/tasks`: Get all tasks (with pagination).
- `GET /api/tasks/:id`: Get a specific task's details.
- `POST /api/tasks`: Create a new task.
- `PUT /api/tasks/:id`: Edit an existing task.
- `DELETE /api/tasks/:id`: Delete a task.

### Users
- `GET /api/users`: Get all users (admin only).
- `POST /api/users`: Add a new user (admin only).
- `DELETE /api/users/:id`: Remove a user (admin only).

---

## Future Improvements
- Enhanced reporting and analytics for task progress.
- Push notifications for upcoming task deadlines.
- Multi-language support for better accessibility.

---
![Screenshot (87)](https://github.com/user-attachments/assets/a479cf70-dee3-4906-ac44-19a3c3baa623)
![Screenshot (88)](https://github.com/user-attachments/assets/8d0d0e12-b3c6-43a5-b5b0-668596f312fa)
![Screenshot (89)](https://github.com/user-attachments/assets/2e3671d1-ed80-49d2-a279-6648f1b5918f)
![Screenshot (90)](https://github.com/user-attachments/assets/650b7de7-2126-416c-97d8-be4272e8b125)
![Screenshot (91)](https://github.com/user-attachments/assets/57302d3e-158f-4ef6-a6a8-b097eb18072f)
