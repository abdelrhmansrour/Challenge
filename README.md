# Challenge

## Overview

This repository contains a simple web application with two main components:

1. **API**: Written in Laravel PHP, the API serves as the backend for the application and listens on port 8000.
2. **Client**: Developed using Nuxt.js, the client is the frontend of the application and listens on port 3000.

### Environment Variables

- **API Directory**: Take a look at the `.env` file in the API directory. It should contain the necessary credentials to connect to the database.

  ```env
    DB_CONNECTION=mysql
    DB_HOST=db
    DB_PORT=3306
    DB_DATABASE=bookapi
    DB_USERNAME=app
    DB_PASSWORD=password
  ```

- **Client Directory**: Check the `.env` file in the Client directory. It should contain the connection string to connect to the API.

  ```env
    VITE_API_URL=http://api:8000
  ```
### Runing the application
     
  - Build and run the Docker image using docker compose
     
  ```env
     docker-compose up --build
  ```
      
### Screenshots 

  Here's a screenshot from terminal for building the containers and running it
  
  ![image](https://github.com/user-attachments/assets/3c412d84-0fc9-4fc8-8aaf-d174f23df848)


 Here's Nuxt.js working in previw mode
 
 ![image](https://github.com/user-attachments/assets/2b538880-0959-485e-b6aa-b332e1783a02)


 Using self signed certificate
 
 ![image](https://github.com/user-attachments/assets/4358448d-2c3f-4506-8832-cf0551da64af)


 Nginx server working fine
 
 ![image](https://github.com/user-attachments/assets/fc9b94d2-6c5a-4efa-ba1c-c2491b86deba)
