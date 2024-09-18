# CODETECH-internship-task-1
NAME:sodanapalli Naga praneetha
COMPANY:CODETECH IT SOLUTIONS
ID:CTO8DS8172
DURATION:sep15/2024-oct15/2024
MENTOR:NEELA SANTHOSH KUMAR

## Project Overview

This project is a simple, user-friendly to-do list web application built using HTML, CSS, and JavaScript. The app allows users to add, toggle, and delete tasks, with the list persisting in the browser's local storage.

## Features

1. Add new tasks
2. Mark tasks as completed
3. Delete tasks
4. Persistent storage using browser's local storage

## Technical Stack

- HTML5
- CSS3
- JavaScript (ES6+)

## File Structure

The entire application is contained in a single HTML file, which includes embedded CSS and JavaScript.

## HTML Structure

The HTML structure consists of:

1. A heading (<h1>) for the app title
2. A form (<form>) for adding new tasks
3. An unordered list (<ul>) for displaying tasks

## CSS Styles

The CSS is embedded in the <style> tag and provides:

1. Basic layout and centering of the app
2. Styling for the form, input, and buttons
3. Styling for the task list and individual task items
4. Styles for completed tasks

## JavaScript Functionality

The JavaScript code provides the following functionality:

1. renderTodos(): Renders the list of todos
2. addTodo(text): Adds a new todo to the list
3. toggleTodo(index): Toggles the completed status of a todo
4. deleteTodo(index): Removes a todo from the list
5. saveTodos(): Saves the current todo list to local storage

Event listeners are set up to handle form submission and button clicks.

## Local Storage

The app uses the browser's local storage to persist the todo list. The todos are saved as a JSON string and retrieved when the page loads.

## User Interface

The user interface is simple and intuitive:

1. An input field for entering new tasks
2. An "Add" button to submit new tasks
3. A list of tasks, each with "Toggle" and "Delete" buttons
4. Completed tasks are visually distinct with a strike-through style

## How to Use

1. Open the HTML file in a web browser
2. Enter a task in the input field and click "Add" or press Enter
3. Click "Toggle" to mark a task as completed or uncompleted
4. Click "Delete" to remove a task from the list

## Future Enhancements

Possible future enhancements could include:

1. Due dates for tasks
2. Task categories or tags
3. Sorting and filtering options
4. User accounts and cloud synchronization
5. Responsive design for mobile devices

## Conclusion

This to-do list web app provides a solid foundation for task management. Its simplicity makes it easy to use and maintain, while the use of local storage ensures that users' tasks persist between sessions.


