# Book Review Application

## Overview
This project is a backend application for managing book reviews, created as part of a hands-on lab and practice project. The application allows users to perform CRUD operations on book reviews with JWT and session authentication. The server-side application is implemented as a RESTful web service using Node.js and Express.js.

## Features
- Retrieve a list of all books available in the bookshop
- Search for specific books based on ISBN, author names, and titles
- Retrieve reviews/comments for specified books
- Register as a new user
- Login to the application
- Add a new review for a book (logged-in users only)
- Modify a book review (logged-in users can modify only their own reviews)
- Delete a book review (logged-in users can delete only their own reviews)

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


## Tasks

### Registering a New User

![Registering a New User](screenshots/register.png)

### Logging in as a User

![Logging in as a User](screenshots/login.png)

### Retrieving All Books

![Retrieving All Books](screenshots/books.png)

### Searching for a Book by ISBN

![Searching for a Book by ISBN](screenshots/search.png)

### Adding a New Review

![Adding a New Review](screenshots/add_review.png)

### Modifying a Review

![Modifying a Review](screenshots/modify_review.png)

### Deleting a Review

![Deleting a Review](screenshots/delete_review.png)

## API Testing

All APIs have been thoroughly tested using Postman to ensure they function correctly. Axios has been used for handling asynchronous operations in the application.


## Contact

For inquiries and support, you can reach me at [your-email@example.com](mailto:sumitdey.cnd@gmail.com).