# LMS Backend

This is the backend codebase for a Learning Management System (LMS). The backend is responsible for handling data storage, user authentication, course management, and other server-side functionalities.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Tokens (JWT) for authentication

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/lms-backend.git


2. Install dependencies:
cd lms-backend
npm install


3. Configure environment variables:
- Create a `.env` file in the root directory.
- Define the following environment variables:
  ```
  PORT=3000
  MONGODB_URI=mongodb://localhost/lms
  JWT_SECRET=yoursecretkey
  ```

4. Start the server:
npm start


## API Documentation

- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Log in an existing user.
- **GET /api/courses**: Get a list of available courses.
- **GET /api/courses/:id**: Get details of a specific course.
- **POST /api/courses**: Create a new course.
- **PUT /api/courses/:id**: Update an existing course.
- **DELETE /api/courses/:id**: Delete a course.
