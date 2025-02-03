# -MyResume

PE02
The application filters and responds on click to the list of movies in React below. Let's describe some aspects of this React application by the input-process-output model:

Input:

The program does not take any kind of user input.
Process:

Predefined movie data gets loaded with title, genre, and release year.
It controls the selected genre state based on user interactions with the dropdown menu.
It filters the application according to the genre that the user selected. If the selected is "All Genres," the app would then show all movies.
It handles the click of a user on movie titles.
Output:

It shows a movie list application that includes title, genre, and release year. Filter the movies by genre using the drop-down menu. Clicking a movie title triggers an alert message displaying the clicked movie's title.

PE03
The React Todo List App is a simple and effective app through which one can dynamically add and remove items. It employs useState hook for storing and updating both current value (task) and list of items (tasks).

When the "Add Task" button is pressed and a task is added in the field, addTask function is run. In it, a quick field checking for an empty field is executed, and then a new task is added to state of tasks, and then field is cleared.

Each task is represented in a <ul> with a "Delete" button adjacent to it. Clicking the button triggers a deleteTask function, excluding current selection and updating state.

The app utilizes CSS for manipulating layout, maintaining proper positioning for the add button, input field, and task list in position. Overall, the React app accurately reflects state management and event handling for dynamically updating UI.