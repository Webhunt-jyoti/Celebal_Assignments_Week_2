# Celebal_Assignments_Week_2
# React Todo List App

A simple yet powerful Todo list app built with React, featuring:
- Add, Edit, Delete Tasks
- Completion toggle with clickable checkbox
- Filtering: All / Completed / Incomplete 
- Sorting: Alphabetical, Completion Status
- Local Storage persistence
- Form input validation
- Custom styling with responsive layout



-- How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Celebal_Assignments_Week_2.git
   cd Celebal_Assignments_Week_2

2. Install dependencies:
   npm install
3. Start the app:
   npm run dev  # for Vite
   OR
   npm start    # for Create React App

|------------------------------------------------------------|
|------------------------------------------------------------|
Testing Guidance 
Use the steps below to manually test key features of the Todo App:

a) Task Operations  --->
   Add Task:
      Enter a valid task and click Add → it appears in the list.
      Leave input empty and click Add → shows error message (validation works).
   Edit Task:
      Click ✏️ icon → changes to editable field.
      Make edits and save → updates task.
   Delete Task:
      Click 🗑️ icon → removes the task from the list.

b) Completion Handling  --->
   Mark as Complete:
      Click the checkbox (left of the task) → task text is struck through.
      Click again to unmark → status toggles correctly.
      Hover on checkbox → cursor turns to hand (pointer style).

C) Filtering Options
   Click on:
      All → shows all tasks.
      Completed → shows only completed tasks.
      Incomplete → shows only tasks not completed.

D) Sorting Options
   Select from dropdown:
      A → Z → tasks sorted alphabetically.
      Status → incomplete shown first.
      Default → original order retained.

E) Persistence (Local Storage)
      Add tasks → refresh the browser → previously added tasks still appear.


