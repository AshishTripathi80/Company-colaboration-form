# Company Collaboration Form

## Overview

**Company Collaboration Form** is a streamlined platform designed to facilitate collaboration and communication within an organization. It serves as a minified version of social media, specifically tailored to the needs of companies. This platform allows team members to interact, share updates, and collaborate on projects in a structured and organized manner.

## Features

- **User Profiles**: Create and manage individual profiles for team members.
- **Activity Feed**: Share updates, announcements, and posts visible to all members.
- **Comments and Reactions**: Engage with posts through comments and reactions.
- **Project Collaboration**: Create project-specific groups for focused collaboration.
- **Notifications**: Receive notifications for mentions, replies, and other important activities.
- **Search Functionality**: Easily search for posts, projects, and team members.

## Technology Stack

- **Frontend**: Angular
  - Dynamic user interface for interaction and collaboration.
  - Responsive design for seamless use across devices.
- **Backend**: Spring Boot
  - RESTful API for handling data and business logic.
  - Integration with databases for persistent storage.
  
## Installation

### Prerequisites

- **Node.js** and **npm** (for Angular)
- **Java 8+** (for Spring Boot)
- **MySQL** or **MongoDB** (depending on your database choice)

### Frontend Setup (Angular)

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Start the Angular development server:
   ```bash
   ng serve
   ```
4. Open a browser and navigate to `http://localhost:4200`.

### Backend Setup (Spring Boot)

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Configure the database connection in `application.properties`.
3. Build the Spring Boot application:
   ```bash
   ./mvnw clean install
   ```
4. Run the Spring Boot application:
   ```bash
   java -jar target/company-collab-form.jar
   ```
5. The backend will be accessible at `http://localhost:8080`.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request for review.


## Contact

For any inquiries or support, please reach out to [Your Name](mailto:your.email@company.com).

---

Feel free to customize this README further based on your specific project details and requirements!
