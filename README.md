# Schedule Marker

**Schedule Marker** is a simple web application that helps users manage their to-do lists along with due dates. Users can add tasks, assign deadlines, and delete tasks as they are completed.

## Features

- **Add To-Do Items**: Input tasks with a due date.
- **Delete To-Do Items**: Remove tasks from the list once completed.
- **Dynamic Task List**: The list updates as tasks are added or removed.

## How to Use

1. **Add a To-Do**: 
   - Enter your task in the `ENTER YOUR TODOS` field.
   - Select a due date.
   - Click the **ADD** button to add the task to the list.
   
2. **View and Delete To-Dos**: 
   - Tasks will appear in the list with their associated due dates.
   - Click the **DELETE** button to remove any task from the list.

## Code Overview

### HTML

The structure includes:
- A title (`SCHEDULE MARKER`).
- Input fields for to-do items and due dates.
- An "Add" button to add tasks to the list.
- A dynamic list that updates when tasks are added or deleted.

### CSS

Basic styling includes:
- **Grid Layout**: Aligns the input section and task list for readability.
- **Button Styling**: Colors and padding for the add and delete buttons to indicate functionality.

### JavaScript

The JavaScript functions handle the app logic:
- **Add Task**: `todoupdate()` pushes a new task with a due date into an array.
- **Delete Task**: Tasks are removed using the `splice()` method, and the list is re-rendered.
- **List Update**: The `loopevent()` function updates the displayed list every time a task is added or deleted.
