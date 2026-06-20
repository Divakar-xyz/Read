# Readify

Readify is a web-based book management application that allows users to manage books and authors through a simple and user-friendly interface. The application provides features for adding, viewing, updating, and deleting books and authors while storing data in MongoDB.

## Features

* Add, edit, view, and delete authors
* Add, edit, view, and delete books
* Store book details such as title, author, publication date, page count, description, and cover image
* Search authors by name
* Search books by title and publication date
* Responsive and clean user interface
* MongoDB database integration using Mongoose

## Technologies Used

### Frontend

* HTML
* CSS
* EJS (Embedded JavaScript Templates)

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Additional Libraries

* FilePond (Image Upload Handling)
* Method Override
* Body Parser
* Dotenv

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd readify
```

3. Install dependencies

```bash
npm install
```

4. Create a `.env` file in the root directory

```env
DATABASE_URL=mongodb://127.0.0.1:27017/readify
```

5. Start MongoDB

6. Run the application

```bash
npm start
```

or

```bash
nodemon server.js
```

7. Open your browser and visit

```text
http://localhost:3000
```

## Project Structure

```text
readify/
│
├── models/
├── routes/
├── views/
├── public/
├── .env
├── package.json
└── server.js
```

## Future Enhancements

* User authentication and authorization
* Book categories and genres
* Book ratings and reviews
* Dashboard with statistics
* Advanced search and filtering
* Cloud image storage



This project is developed for educational and learning purposes.
