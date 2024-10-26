# React Todo App

## Overview

This is a **Todo App** built using **ReactJS**. It allows users to manage tasks by adding, viewing, completing, and deleting them. The app provides a clean and interactive UI, making task management intuitive and efficient. Additionally, the app saves your task list in the browser's local storage, ensuring that your tasks persist even after refreshing or closing the app.

This project was developed as a hands-on learning experience with React, focusing on core features such as state management, component hierarchy, and event handling.

## React Features Implemented

In building this project, I learned and applied several fundamental React concepts:

- **State Management with `useState`**:  
  Used to track tasks, the currently selected tab (All, Open, Completed), and form input.
  
- **Component Lifecycle with `useEffect`**:  
  Implemented to load tasks from `localStorage` on initial render and save tasks to `localStorage` after any updates.
  
- **Props Passing**:  
  Shared data between components via props to ensure components remain reusable and flexible.

- **Event Handling**:  
  Handled button clicks and input changes to update task status, add tasks, and manage tab switching.
  
- **Conditional Rendering**:  
  Displayed different sets of tasks (all, open, or completed) based on the selected tab.

## Features of the App

- **Add New Tasks**:  
  Allows users to add new tasks using an input field and button.
  
- **Task Status Management**:  
  Tasks can be marked as completed with a simple click.
  
- **Delete Tasks**:  
  Provides an option to delete tasks that are no longer needed.

- **Task Filtering**:  
  Users can filter tasks based on their status (All, Open, or Completed).

- **Persistent Storage**:  
  Tasks are saved in `localStorage` to ensure data persistence even after refreshing the browser.

- **Dynamic Task Counter**:  
  The app dynamically displays the number of tasks remaining, with pluralization support (e.g., "1 task" or "2 tasks").

- **Responsive UI**:  
  The app features a simple and responsive design with tabs for easy navigation.

## Project Structure

The app is organized into several components:

- **App.jsx**:  
  The main component that manages state and renders the app’s layout. It connects the header, tabs, task list, and input components.

- **Header.jsx**:  
  Displays the task count dynamically.

- **Tabs.jsx**:  
  Renders the tabs for filtering tasks (All, Open, Completed) and shows the count of tasks per category.

- **TodoList.jsx**:  
  Displays the list of tasks based on the currently selected tab.

- **TodoCard.jsx**:  
  Represents an individual task card that shows the task's name and buttons to mark as complete or delete.

- **TodoInput.jsx**:  
  Handles task creation, including input validation to prevent empty tasks from being added.

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app-react.git

2. Navigate to the project directory:

   ```bash
   cd todo-app-react

3. Install the dependencies:

   ```bash
   npm install

4. Start the development server:

   ```bash
   npm start

5. Open the app in your browser at http://localhost:3000

## Usage

- Add a task by typing into the input field and pressing the `+` button.
- View tasks in different tabs: "All", "Open", or "Completed".
- Click on a task to mark it as completed.
- Delete a task by clicking the delete button on the task card.

## Built With

- **ReactJS**: A JavaScript library for building user interfaces.
- **HTML & CSS**: For structuring and styling the app.
- **LocalStorage**: For persisting the task list across browser sessions.

## Future Enhancements

- **Edit Task Functionality**:  
  Allow users to edit the text of existing tasks.
  
- **Due Date Feature**:  
  Add a due date for tasks and the ability to sort tasks based on urgency.

- **Task Prioritization**:  
  Enable users to prioritize tasks, displaying them in order of importance.

- **Dark Mode**:  
  Implement a toggle for switching between light and dark themes.
