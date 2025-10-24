# Spring Boot + Next.js Boilerplate  

This repository provides a minimal boilerplate for a full‑stack web application with a Spring Boot backend and a Next.js frontend. The backend serves RESTful APIs, while the frontend is a React‑based SSR application.  

## Structure  
- `backend/` – Spring Boot application, built with Maven.  
- `frontend/` – Next.js application.  

## Getting Started  

### Backend (Spring Boot)  
1. Navigate to the `backend` directory.  
2. Ensure you have Java 17 and Maven installed.  
3. Install dependencies and run the application:  

   ```bash  
   mvn spring-boot:run  
   ```  

The backend will start on [http://localhost:8080](http://localhost:8080) and expose a sample route at `/hello` returning a greeting.  

### Frontend (Next.js)  
1. Navigate to the `frontend` directory.  
2. Install the dependencies:  

   ```bash  
   npm install  
   ```  

3. Start the development server:  

   ```bash  
   npm run dev  
   ```  

The frontend will run on [http://localhost:3000](http://localhost:3000) with a simple page and an API route at `/api/hello`.  

## Usage  

- Access the Next.js frontend at `http://localhost:3000` to see a welcome message.  
- Access the Spring Boot API at `http://localhost:8080/hello` for a backend greeting.  

## Notes  

This project skeleton is intended to be a starting point. Feel free to expand the backend with additional controllers and the frontend with more pages and API routes as needed.
