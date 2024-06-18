# Book Review Application

## Overview
This project is a backend application for managing book reviews, created as part of a hands-on lab and practice project. The application allows users to perform CRUD operations on book reviews with JWT and session authentication. The server-side application is implemented as a RESTful web service using Node.js and Express.js.

## Features
- Retrieve a list of all books available in the bookshop.
- Search for specific books based on ISBN, author names, and titles.
- Retrieve reviews for specified books.
- Register as a new user.
- Login to the application.
- Add a new review for a book (logged-in users only).
- Modify a book review (logged-in users can modify only their own reviews).
- Delete a book review (logged-in users can delete only their own reviews).

## Files and folders
The router directory having the below 3 files:

-booksdb.js - This contains the the preloaded book information for this application.
-general.js - This contains the skeletal implementations for the routes which a general user can access.
-auth_users.js - This contains the skeletal implementations for the routes which an authorized user can access.

The root directory has:
-index.js - This is the main file of the application.

## Packages

{
"dependencies": {
    "axios": "^1.7.2",
    "express": "^4.18.1",
    "express-session": "^1.18.0",
    "jsonwebtoken": "^8.5.1",
    "nodemon": "^2.0.19"
  }
}

-express: A fast, unopinionated, minimalist web framework for Node.js.
-express-session: A middleware for session handling in Express applications.
-jsonwebtoken: A library to work with JSON Web Tokens (JWT) for authentication.
-nodemon: A utility that automatically restarts your node application when file changes in the directory are detected.
-axios: A promise-based HTTP client for the browser and Node.js.

## Installation
To run this project locally, follow these steps:-

1. Clone the repository:
   ```bash
   git clone https://github.com/sd-cnd/expressBookReviews.git

2. Navigate to the project directory:
   ```bash
   cd final-project

3. Install the dependencies::
   ```bash
   npm install

4. Start the application::
   ```bash
   npm run start


## Tasks :-

### Task 1 : Retrieving All Books

![Retrieving All Books](https://i.postimg.cc/mkFNXxQS/1-getallbooks.png)

### Task 2 : Searching for a Book by ISBN

![Searching for a Book by ISBN](https://i.postimg.cc/qRWZMxwj/2-gedetails-ISBN.png)

### Task 3 : Searching for a Book by author

![Searching for a Book by author](https://i.postimg.cc/RhcGC5NZ/3-getbooksbyauthor.png)

### Task 4 : Searching for a Book by title

![Searching for a Book by title](https://i.postimg.cc/287TPDsH/4-getbooksbytitle.png)

### Task 5 : Searching for a Book review by ISBN

![Searching for a Book review by ISBN](https://i.postimg.cc/Jzh3vBcn/5-getbookreview.png)

### Task 6 : Registering a New User

![Registering a New User](https://i.postimg.cc/15mDVNdH/6-register.png)

### Task 7 : Logging in as a User

![Logging in as a User](https://i.postimg.cc/c19LTgHT/7-login.png)

### Task 8 : Adding and modifying reviews as logged-in user

![Adding a New Review](https://i.postimg.cc/Dy4ngxRy/8-reviewadded.png)

### Task 9 : Deleting a review as logged-in user

![Code Snippet](https://i.postimg.cc/nVgtCvM8/9-deletereview.png)

### Task 10 : Added the code for getting the list of books available in the shop (done in Task 1) using Promise callbacks or async-await with Axios.

![Code Snippet](https://i.postimg.cc/R0Xk9t2D/task10.png)

### Task 11 : Add the code for getting the book details based on ISBN (done in Task 2) using Promise callbacks or async-await with Axios.

![Code Snippet](https://i.postimg.cc/13HmnfLp/task11.png)

### Task 12 : Add the code for getting the book details based on Author (done in Task 3) using Promise callbacks or async-await with Axios.

![Code Snippet](https://i.postimg.cc/139PQyf4/task12.png)

### Task 13 : Add the code for getting the book details based on Title (done in Task 4) using Promise callbacks or async-await with Axios.

![Code Snippet](https://i.postimg.cc/Zq21CmK8/task13.png)

## API Testing

All APIs have been thoroughly tested using Postman to ensure they function correctly.

## Contact

For inquiries and support, you can reach me at [sumitdey.cnd@gmail.com](mailto:sumitdey.cnd@gmail.com).