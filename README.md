# CODTECH-Task1

Name: AKSHITHA DUSA
Company: CODTECH IT SOLUTIONS
ID:CTO8WD447
Domain: Web Development
Duration: May 20 - June 20
Mentor: SRAVANI GOUNI

Overview of the Project:

Project: To create a TO-DO List by using HTML, CSS, JS.

1. HTML Structure (index.html)

The HTML file sets up the basic structure of the todo list application:

    Document Type Declaration: <!DOCTYPE html> specifies the document type and version of HTML.
    Viewport Meta Tag: <meta name="viewport" content="width=device-width, initial-scale=1.0"> ensures proper scaling on mobile devices.
    Title: <title>Todo List</title> sets the title of the webpage.
    CSS Link: <link rel="stylesheet" href="styles.css"> links the CSS file for styling.
    Body Content: Contains a <div class="container"> that wraps the main content of the application.
        Heading: <h1>Todo List</h1> provides a title for the todo list.
        Form: <form id="todo-form"> includes an input field (<input type="text" id="todo-input">) for adding tasks and a submit button (<button type="submit">Add Task</button>).
        Task List: <ul id="todo-list"></ul> is an unordered list where tasks will be dynamically added.

2. CSS Styling (styles.css)

The CSS file (styles.css) styles the HTML elements to create a visually appealing and functional interface:

    Container Styling: Defines the layout and appearance of the main container (<div class="container">).
    Form Styling: Styles the form elements (input, button) for task input and submission.
    List Styling: Defines the appearance of the task list (<ul>) and list items (<li>).
    Completed Tasks: Uses the .completed class to apply a line-through effect for completed tasks.
    Delete Button: Styles the delete button (<button class="delete-btn">Delete</button>) with a red background and hover effect.

3. JavaScript Functionality (app.js)

The JavaScript file (app.js) adds dynamic functionality to the todo list:

    Event Listener: Uses DOMContentLoaded event to ensure the DOM is fully loaded before executing JavaScript code.
    Form Submission: Listens for form submission (todoForm.addEventListener('submit', function(event) {...}) to add tasks.
    Adding Tasks: Defines addTask(taskText) function to create new list items (<li>) with task text and delete button.
    Deleting Tasks: Provides functionality to delete tasks by clicking the delete button (<button class="delete-btn">Delete</button>).
    Completing Tasks: Toggles the .completed class on list items to mark tasks as completed or incomplete.

4. Functionality Overview

    Adding Tasks: Users can enter a task in the input field and press Enter or click "Add Task" to add it to the list dynamically.
    Completing Tasks: Clicking on a task toggles a line-through effect (text-decoration: line-through;) to visually indicate completion.
    Deleting Tasks: Each task has a delete button that removes the corresponding task from the list when clicked.

5. Enhancements

    Persistence: Implement local storage to save tasks so they persist across page refreshes.
    Validation: Add input validation to ensure users enter valid task names.
    Sorting and Filtering: Implement features to sort tasks by date, priority, or category.
    Responsive Design: Ensure the application looks and functions well on various screen sizes and devices.

Conclusion

This simple todo list application demonstrates the fundamental concepts of frontend web development using HTML, CSS, and JavaScript.

![Screenshot from 2024-06-18 23-37-00](https://github.com/AkshithaDusa8/CODTECH-Task1/assets/173191138/82bf940b-5f68-44e6-94c5-6443dcd3de9a)

