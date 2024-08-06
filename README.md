PostifyAPI

PostifyAPI is an API-based application built with Express and Node.js. It enables users to manage blog posts with ease, offering functionalities to add, delete, view, and rename posts. The API endpoints are thoroughly tested using Postman, ensuring reliable and efficient blog content management.

Features
Add Posts: Create new blog posts.
Delete Posts: Remove existing blog posts.
View Posts: Retrieve and view blog posts.
Rename Posts: Update the title of existing blog posts.

Technologies Used
Node.js
Express.js
EJS
Postman (for testing)

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/PostifyAPI.git

Navigate to the project directory:
cd PostifyAPI

Install dependencies:
npm install


Start the server:
npm start


Use Postman to interact with the API endpoints.
GET /posts: Retrieve all posts.

POST /posts: Add a new post.

DELETE /posts/:id
: Delete a post by ID.

Patch /posts/:id

: Rename a post by ID.

Testing
Use Postman to test the API endpoints:
Import the Postman collection provided in the repository.
Run the requests to interact with the API.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

