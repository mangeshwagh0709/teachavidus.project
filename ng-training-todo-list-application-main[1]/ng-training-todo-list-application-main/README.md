
# To-Do List Application

## Assignment Overview
This project is a full-stack To-Do List Application developed using **Node.js** with **Express.js** for the backend and **Angular** for the frontend. The application allows users to create, read, update, and delete tasks from their to-do list, stored in **MongoDB**.

## Features
- **Add Task**: Users can add new tasks with relevant details.
- **View Tasks**: Display a list of all tasks stored in the application.
- **Edit Task**: Update existing tasks with new information.
- **Delete Task**: Remove tasks from the to-do list.
- **Responsive Design**: The frontend is designed to be user-friendly and fully responsive for both desktop and mobile views.
- **APIs**: 
  - `GET /api/tasks` - Retrieve all tasks.
  - `POST /api/task` - Create a new task.
  - `PUT /api/task/:id` - Update a task by ID.
  - `DELETE /api/task/:id` - Delete a task by ID.
- **Unit Testing**: 
  - Backend: Unit tests are written using **Mocha** for API endpoints.
  - Frontend: Angular's default unit testing library is used to ensure UI functionality.

## Technologies Used
### Server-Side:
- **Node.js** with **Express.js**: Backend server and routing.
- **MongoDB**: NoSQL database for storing tasks.
- **Mongoose**: ODM for MongoDB.
- **Mocha**: Unit testing for the server-side code.

### Client-Side:
- **Angular**: Framework for building the frontend.
- **Angular Components**:
  - **Task List Component**: Displays the list of tasks.
  - **Task Form Component**: A form for creating and updating tasks.
- **Task Service**: Handles API communication with the backend.
- **Responsive UI**: Designed to be mobile and desktop-friendly.
- **Angular CLI**: For building, running, and testing the frontend.


## Getting Started

### Prerequisites
- **Node.js** (version 14 or higher)
- **MongoDB** (local or cloud instance)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/VaibhavRajput884/Todo-List-Application
   cd Todo-List-Application
   ```

### Install Dependencies

#### Backend (in `/server` directory):
```bash
cd server
npm install
```

#### Frontend (in `/client` directory):
```bash
cd client
npm install
```

### Create a `.env` file
In the `/server` directory, create a `.env` file and add the following:

```bash
MONGO_URL=mongodb://localhost:27017/todo-list-Application
PORT=5000
```

### Running the Application

#### Start Backend:
```bash
cd server
npm run dev
```

#### Start Frontend:
```bash
cd client
ng serve
```

The backend will run on `http://localhost:5000` and the frontend on `http://localhost:4200`.