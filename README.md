# My Todo App

## Overview
This is a simple, single-page web application that allows users to manage their daily tasks. It features the ability to add new todo items, mark them as complete or incomplete, and delete them. The app's state is persisted using local storage, so your tasks remain even after closing and reopening the browser.

## Setup
To set up and run this application:
1.  **Save the file:** Save the provided `index.html` content into a file named `index.html` on your computer.
2.  **Open in browser:** Open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Safari, Edge). You can do this by double-clicking the file.

No additional dependencies or server setup are required as all the HTML, CSS, and JavaScript are contained within a single HTML file.

## Usage
1.  **Add a Todo:**
    *   Type your task into the input field labeled "Add a new todo...".
    *   Click the "Add Todo" button or press `Enter` on your keyboard.
    *   The new todo item will appear in the list below.

2.  **Mark as Complete/Unmark:**
    *   Each todo item has a "Complete" button.
    *   Clicking this button will toggle the task's completion status.
    *   Completed tasks will have a strikethrough text and a slightly different background color. The button text will change to "Unmark".
    *   Clicking "Unmark" will revert the task to incomplete.

3.  **Delete a Todo:**
    *   Each todo item has a "Delete" button.
    *   Clicking this button will permanently remove the task from your list.

4.  **Persistence:**
    *   All your added, completed, and deleted todos are saved automatically in your browser's local storage. They will be available the next time you open the app in the same browser.