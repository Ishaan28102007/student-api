# Student Management API

A simple Student Management REST API built using Node.js, Express.js, and MongoDB.

## Features

- Add a new student
- View all students
- Update student details
- Delete a student
- Store student data in MongoDB Atlas

## Technologies Used

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ishaan28102007/student-api.git
   ```

2. Open the project folder:

   ```bash
   cd student-api
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root folder and add your own MongoDB connection string:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   ```

5. Start the server:

   ```bash
   npm run dev
   ```

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /api/students | Add student |
| GET | /api/students | Get all students |
| PUT | /api/students/:id | Update student |
| DELETE | /api/students/:id | Delete student |

## Testing

All API operations are tested using Postman.

## Author

Ishaan Dudeja
