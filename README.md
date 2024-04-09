# Simple CRUD API Project

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
This project is a simple CRUD (Create, Read, Update, Delete) API built using PHP Laravel framework. It provides endpoints for managing blog posts, allowing users to create, retrieve, update, and delete posts. This project can be used as a template for users portfolio's.

## Getting Started
These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites
Before you begin, make sure you have the following installed:
- PHP >= 7.3
- Composer
- MySQL
- Git

## Installing
1. Clone the repository:
   ```bash
   git clone https://github.com/Aaron-Riley/Simple-CRUD-API.git
2. Install dependencies using Composer:
   ```bash
   composer install
3. Set up your environment variables by copying the .env.example file to .env:
   ```bash
   cp .env.example .env
4. Update the database configuration in the .env file with your MySQL credentials.
5. Generate an application key:
   ```bash
   php artisan key:generate
6. Run the database migrations to create the necessary tables:
   ```bash
   php artisan migrate

## Usage
Once the API is set up, you can use tools like Postman or curl to interact with the endpoints. Here are the available endpoints:

- GET /posts: Retrieve all blog posts
- POST /posts: Create a new blog post
- GET /posts/{id}: Retrieve a single blog post by its ID
- PUT /posts/{id}: Update an existing blog post
- DELETE /posts/{id}: Delete a blog post by its ID

Make sure to replace {id} with the actual ID of the blog post when making requests to the individual post endpoints.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

