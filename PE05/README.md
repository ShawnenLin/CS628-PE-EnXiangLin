Input
The application launches with an existing collection of recipes. Users can add new recipes by entering details—such as name, ingredients, instructions, and cooking time—into a form and clicking the "Save Recipe" button. Additionally, users can view, update, or delete any of the current recipes.

Process
When a user fills out the form and submits it, the recipe information is sent to the database. The frontend, developed with React using useState and useEffect, manages both the recipe list and the form inputs. The backend, built with Express and MongoDB, handles API requests to retrieve, insert, update, or delete recipes. After a recipe is successfully added or updated, the application automatically redirects the user back to the recipe list. Every recipe is presented as a clickable item, linking to a detailed view where users can further edit or delete that recipe.

Output
The recipe list is displayed as clickable menu options. Selecting a recipe takes the user to a detailed page showing the recipe’s name, ingredients, instructions, and cooking time. Users can update or delete recipes from either the list view or the detail view. Overall, the application provides a simple, organized, and efficient way to manage and update recipe information.