# Sulav's To Do List

## Overview

This To Do List is a simple task management application built using Next.js and React. This application allows users to add tasks with descriptions and delete tasks as needed. The entire application is contained within a single `page.js` file, demonstrating how to build a functional React application without splitting code into multiple components.

## Features

- **Add Tasks**: Users can add tasks with a title and description.
- **Display Tasks**: Tasks are displayed in a list format.
- **Delete Tasks**: Users can delete tasks from the list.
- **Responsive Design**: The application has a responsive and user-friendly interface.

## Concept

The core concept of this application revolves around the use of React's state management and event handling. By using React hooks such as `useState`, the application maintains and updates the list of tasks dynamically. The application consists of a form for adding tasks and a list that displays the tasks with options to delete them.

## Technologies Used

- **Next.js**: A React framework for building server-side rendering and static web applications.
- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling the application.

## Code Structure

The main code resides in a single `page.js` file. Here's an overview of the code structure:

1. **State Management**
   - `title` and `desc` state variables for managing the input values.
   - `mainTask` state variable for managing the list of tasks.
   
2. **Event Handlers**
   - `submitHandler`: Handles the form submission to add a new task.
   - `deleteHandler`: Handles the deletion of a task from the list.
   
3. **Rendering Tasks**
   - Conditionally renders tasks based on the length of `mainTask`.
   - Maps over `mainTask` to display each task with a delete button.

## Installation and Usage

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/sulavs-todo-list.git
   cd sulavs-todo-list
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser**:
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application in action.

