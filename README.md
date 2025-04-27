# Health Program Management System

This project is a system that allows doctors to create health programs, enroll clients into those programs, and register users to the programs. It uses a combination of a Spring Boot backend, MySQL for data storage, and a ReactJS frontend with Tailwind CSS for styling.

## Requirements

Before setting up the project, make sure your system meets the following prerequisites:

### Java Setup (Backend)
1. **Install JDK**: You need to have Java Development Kit (JDK) installed on your system. If you haven't installed it yet, follow the instructions on the [official Oracle website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) to download and install the JDK.
   
2. **Install Development Environment**:
   - **VS Code** or **IntelliJ IDEA** is recommended as the IDE for Java development.
   - **Spring Boot** is used as the backend framework for this project.

3. **MySQL Database**:
   - This system uses MySQL as the database. Once the backend is set up, the database will be created automatically.
   - Ensure that you configure your database credentials in the backend configuration files before running the program.

### Frontend Setup (ReactJS)
1. **Install Node.js and npm**:
   - You need to have [Node.js](https://nodejs.org/) and **npm** (Node Package Manager) installed. Download and install the latest stable version of Node.js which includes npm.

2. **ReactJS**:
   - This system uses **ReactJS** for the frontend. If you're new to React, check the official documentation for [getting started with React](https://reactjs.org/docs/getting-started.html).
   
3. **Tailwind CSS**:
   - This project uses **Tailwind CSS** for styling. Tailwind provides utility-first classes to style your components efficiently.
   - To install Tailwind CSS, run the following commands in the React project directory:
     ```bash
     npm install -D tailwindcss postcss autoprefixer
     npx tailwindcss init
     ```

   - Then, configure the `tailwind.config.js` file and include the Tailwind CSS directives in your CSS files like so:
     ```css
     @tailwind base;
     @tailwind components;
     @tailwind utilities;
     ```

4. **Recommended IDE**:
   - **VS Code** is recommended for the frontend development. It has excellent support for ReactJS and Tailwind CSS through extensions.

## Project Setup

### Backend Setup
1. Clone the backend repository:
   ```bash
   git clone https://github.com/your-username/health-program-backend.git
