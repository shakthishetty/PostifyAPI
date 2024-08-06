PostifyAPI
PostifyAPI is an API-based application built with Express and Node.js. It allows users to manage blog posts with functionalities to add, delete, view, and rename posts. The API endpoints are thoroughly tested using Postman, ensuring reliable and efficient blog content management.

Features
Add Posts: Create new blog posts.
Delete Posts: Remove existing blog posts.
View Posts: Retrieve and view blog posts.
Rename Posts: Update the title of existing blog posts.
Technologies Used
Node.js
Express.js
Postman (for testing)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/PostifyAPI.git
Navigate to the project directory:
bash
Copy code
cd PostifyAPI
Install dependencies:
bash
Copy code
npm install
Usage
Start the server:
bash
Copy code
npm start
Use Postman to interact with the API endpoints.
API Endpoints
GET /get-posts: Retrieve all posts.
POST /post-posts: Add a new post.
DELETE /posts/
: Delete a post by ID.
PUT /posts/
: Rename a post by ID.
Testing
Import the Postman collection provided in the repository.
Run the requests to interact with the API.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.
