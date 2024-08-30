# Articles App

## API Documentation

For detailed API documentation, visit: [Postman Documentation](https://documenter.getpostman.com/view/31592980/2sAXjKaCYU)

## Routes and Methods

| Method | Endpoint                       | Description                              |
|--------|--------------------------------|------------------------------------------|
| **POST**   | `/api/authors/register`           | Register a new author                      |
| **POST**   | `/api/authors/login`              | Log in an existing author                  |
| **POST**   | `/api/authors/logout`             | Log out an author                          |
| **GET**    | `/api/authors`                    | Get a list of all authors                  |
| **GET**    | `/api/authors/:authorId`          | Get a specific author by ID                |
| **PATCH**  | `/api/authors/:authorId`          | Update an existing author's details        |
| **DELETE** | `/api/authors/:authorId`          | Delete an author                           |
| **POST**   | `/api/articles`                   | Create a new article                       |
| **GET**    | `/api/articles`                   | Get a list of all articles                 |
| **GET**    | `/api/articles/:articleId`        | Get a specific article by ID               |
| **PATCH**  | `/api/articles/:articleId`        | Update an existing article                 |
| **DELETE** | `/api/articles/:articleId`        | Delete an article                          |

## Overview

The Articles App allows authors to write and manage articles. Users can read the published articles. The backend is built using Node.js, Express, and MongoDB, and the frontend is developed using Angular.

- **Authors** can register, log in, log out, and manage their profile.
- **Users** can read articles published by authors.

## Run
```bash
npm install
npm run start
```