# CS-340: Client-Server Development

This project was completed for SNHU's CS-340 course and focused on building a maintainable, modular backend using Python and MongoDB. It was split into two parts: a CRUD module and an interactive dashboard designed for a fictional organization (Grazioso Salvare) to simulate a real-world client scenario.

The purpose of the project was to practice backend fundamentals, such as object-oriented design, database integration, and real-time data visualization.

## What I Learned

- How to build maintainable and reusable code using modular, object-oriented design  
- How to separate backend logic (CRUD operations) from the UI/dashboard layer  
- Practical experience designing and querying a NoSQL database (MongoDB)  
- How to structure real-time filtering and display logic for dashboards  
- How indexing and aggregation pipelines can optimize performance  

## Tech Stack

- Language: Python  
- Database: MongoDB  
- Libraries: Flask, PyMongo, Flask-PyMongo  
- Visualization: HTML/CSS with JavaScript dashboard components  
- Tools: VS Code, MongoDB Compass, Postman  

## Key Features

- Reusable CRUD module built using object-oriented Python  
- Real-time data filtering by breed, status, or rescue type  
- MongoDB integration with aggregation pipelines for fast queries  
- Interactive dashboard interface displaying rescue dog data  
- Clean separation of concerns: backend logic decoupled from frontend  
- Indexing for performance improvements on large data sets  

## Key Concepts

### Maintainability and Modularity

The project emphasized separating database logic from the interface layer. A CRUD module was developed using object-oriented principles and integrated cleanly into the dashboard. This modularity makes the system easier to debug, extend, or repurpose for other use cases like adoption systems or inventory tracking.

### Problem-Solving Approach

I approached the assignment by first analyzing the data structure and functional requirements. I then broke the task into manageable components—designing the database schema, coding CRUD functions, and wiring up filters and visualizations. Performance was improved by using indexing and aggregation techniques to efficiently handle real-time updates.

### Why It Matters

Although the client (Grazioso Salvare) was fictional, the challenges were realistic. The dashboard allowed filtering rescue dogs by type, breed, and location, simulating how organizations could use backend tools to make data-informed decisions. Projects like this reinforce how computer science enables automation, insight, and impact in real-world contexts.

## Status

Completed as part of SNHU coursework  
Not a production system — used for educational purposes only
