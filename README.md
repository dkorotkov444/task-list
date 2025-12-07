# task-list

A to-do list web application built with HTML, CSS, and jQuery to demonstrate DOM manipulation and interactive UI features.

## Overview

This is a practical exercise in front-end development, showcasing DOM manipulation techniques, jQuery usage, and UI/UX best practices.

## Features

- **Add Tasks**: Enter task text and click "Add" button to add items to the list
- **Mark Complete**: Double-click any task to strike through (mark as complete)
- **Delete Tasks**: Click the "X" button next to a task to remove it from the list
- **Reorder Tasks**: Drag and drop tasks to reorganize the list using jQuery UI Sortable
- **Input Validation**: Prevents adding empty tasks with an alert notification
- **Auto-clear**: Input field automatically clears after adding a task

## Technologies Used

- **HTML5**: Page structure and semantic markup
- **CSS3**: Styling with responsive layout and hover effects
- **JavaScript**: Core application logic
- **jQuery 3.5.1**: DOM manipulation and event handling
- **jQuery UI 1.12.1**: Sortable functionality for drag-and-drop reordering

## Project Structure

```
task-list/
├── index.html          # Main HTML page
├── css/
│   └── styles.css      # Application styles
├── js/
│   └── scripts.js      # JavaScript functionality
└── README.md           # Project documentation
```

## How to Use

1. Open `index.html` in a web browser
2. Type a task description in the input field
3. Click "Add" or press Enter to add the task to the list
4. **Double-click** a task to mark it as complete (strikethrough effect)
5. Click the **"X"** button to delete a task
6. **Drag tasks** to reorder them as needed

## Code Highlights

### Task Addition (`newItem()`)
- Creates new list items dynamically
- Validates input (prevents empty entries)
- Appends delete button to each item

### Task Completion
- Double-click event toggles `.strike` class
- CSS applies text-decoration styling

### Task Deletion
- Delete button adds `.delete` class
- CSS hides the element with `display: none`

### Drag-and-Drop
- jQuery UI Sortable enables list reordering
- Initialized on the `#list` ordered list element

## Browser Compatibility

Works with all modern browsers that support:
- HTML5
- CSS3
- jQuery 3.5.1
- jQuery UI 1.12.1