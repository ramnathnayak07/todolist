# to-do list

This is a simple, user-friendly To-Do List web application built using HTML, CSS, and JavaScript. It allows users to manage their tasks efficiently, including adding, editing, marking tasks as completed, and deleting them. The app uses the browser's LocalStorage to save tasks, so tasks persist even when the page is reloaded.

To view Project: <a href="https://ramnathnayak07.github.io/todolist/">Click here</a><br>

## Features

- **Frontend**: A clean and stylish contact form interface built using HTML, CSS, and JavaScript.
- **Backend API**: Handles form submissions, performs basic validation, and stores data in an SQLite database.
- **API Integration**: The frontend interacts with the Flask backend via a RESTful API.
- **Database**: Data is persisted using SQLite, but this can be configured to any relational database.

## Technologies Used

- HTML5: Markup language for structuring the web page.
- CSS3: Used for styling the app, including flexbox and grid for layout.
- JavaScript: Adds functionality to the app, including dynamic task management and interaction with LocalStorage.
- Google Fonts: Provides custom fonts for better UI/UX.

Clone the Repository

To get a copy of this project, run the following commands in your terminal:

 ```bash
    git clone https://github.com/ramnathnayak07/todolist-app.git
    cd todo-list-app
```

Run the Project

Once you’ve cloned the project, open the index.html file in any modern web browser to run the application.

## Functionality

- Adding a Task.
- Enter the task content in the input field.
- Choose a category by selecting either Personal or Business.
- Click the "Add todo" button to create the task, which will then appear in the task list.
- Editing a Task.
- Click the "Edit" button next to the task.
- Modify the task content and click outside the input field to save the changes.
- The updated task is saved in LocalStorage.
- Marking a Task as Completed.
- Check the checkbox next to a task to mark it as completed.
- Completed tasks are visually indicated with a strikethrough.
- Uncheck the checkbox to undo marking a task as completed.
- Deleting a Task.
- Click the "Delete" button next to the task.
- The task will be removed from the list and from LocalStorage.

## LocalStorage

The app leverages the browser's LocalStorage to store tasks. This allows users to:

- Save their tasks persistently in the browser.
- Retrieve tasks automatically when they revisit the page.

How it works:
- When tasks are added, updated, or deleted, the tasks are stored as JSON objects in the LocalStorage.
- On page load, the stored tasks are retrieved and displayed.

## Future Improvements

- User Authentication: Introduce user login to allow synchronization of tasks across devices.
- Task Priorities: Add functionality to prioritize tasks (e.g., high, medium, low).
- Due Dates: Enable setting due dates and reminders for tasks.
- Task Filters: Provide filters to show tasks based on categories or completion status.
- Animations and Transitions: Add visual feedback for better user experience when tasks are added, edited, or deleted.
