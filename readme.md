# Forum Project

This project involves creating a web forum where users can communicate with each other, associate categories with posts, like and dislike posts and comments, and filter posts. SQLite is used as the database library to store data such as users, posts, and comments.

## Features

1. **Authentication**
   - Users can register with their email, username, and password.
   - Registration checks for duplicate emails and ensures password encryption.
   - Registered users can log in with their credentials.
   - Session management is implemented using cookies with expiration dates.

2. **Communication**
   - Registered users can create posts and comments.
   - Posts can be associated with one or more categories.
   - Posts and comments are visible to all users.
   - Non-registered users can view posts and comments.

3. **Likes and Dislikes**
   - Registered users can like or dislike posts and comments.
   - The number of likes and dislikes is visible to all users.


## Run

1. Clone the repository to your local machine.
2. Ensure you have Go and Docker installed.
3. Navigate to the project root directory.
4. Traditional way
   1. `go run ./cmd/web`
5. Access the forum at `http://localhost:4000` in your web browser.


## User to login

- login: admin
- password: admin

## Authors 
Temirlan Sadvakassov CSE2405

