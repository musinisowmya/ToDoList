 **HTML Structure**: Includes an input field and button to add tasks, a list (`<ul>`) to display tasks, and filter buttons for `All`, `Active`, and `Completed`.

**CSS Styling**: Adds a clean, responsive look with a centered container, a semi-transparent background, and hover effects for buttons and tasks.

 **Tasks Array**: Stores tasks in memory, with `text` and `completed` properties, and syncs them with `localStorage` to persist data.

 **Task Addition**: Clicking "Add Task" or pressing Enter adds a task to the list if the input is not empty.

 **Task Rendering**: Dynamically displays tasks, applying filters based on the selected button (`All`, `Active`, `Completed`).

 **Task Completion**: Clicking the check button toggles a task's completion status (strikes through completed tasks).

 **Task Deletion**: Clicking the delete button removes the task from the list and updates `localStorage`.

 **Filtering**: Filter buttons switch views between all tasks, active tasks, and completed tasks.

 **Persistent Storage**: Saves and retrieves tasks from `localStorage` for data persistence.

 **Interactivity**: Smooth animations and transitions are added for buttons and task hover effects.
