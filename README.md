# Blog API Project

This project is a **Blog API** demonstrating how backend development and APIs work using **Node.js**, **Express.js**. The API allows users to create, read, update, and delete blog posts.

## Features
- **RESTful API** for blog posts
- **Express.js** for backend routing
- **Body-parser** for handling request data

## Technologies Used
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web framework for Node.js
- **Axios** - HTTP client for requests
- **EJS** - Template engine for rendering views

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/anubhab0709/blog-api.git
   cd blog-api
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the API server:
   ```sh
   node index.js
   ```
   The API will start at `http://localhost:4000`.
4. Run the frontend server:
   ```sh
   node server.js
   ```
   The frontend will be available at `http://localhost:3000`.

## API Endpoints

| Method | Endpoint         | Description                     |
|--------|-----------------|---------------------------------|
| GET    | `/posts`        | Get all blog posts              |
| GET    | `/posts/:id`    | Get a specific blog post        |
| POST   | `/posts`        | Create a new blog post          |
| PATCH  | `/posts/:id`    | Update a blog post partially    |
| DELETE | `/posts/:id`    | Delete a blog post              |

## Usage
- You can use **Postman** or **cURL** to test the API.
- The frontend fetches blog posts and allows users to create and modify them.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License
This project is open-source and available under the **MIT License**.

## Author
Developed by **[Anubhab Bhattacharjee]**.

