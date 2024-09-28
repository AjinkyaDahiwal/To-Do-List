# To-Do List App
This is a simple To-Do List web application that allows users to add, delete, and check off tasks. The app uses local storage to persist data, so tasks remain saved even after the page is refreshed.

# Features : 
- Add new tasks to the list.
- Mark tasks as completed by clicking on them.
- Delete tasks using the close (×) button.
- Tasks persist in the browser's local storage, allowing users to retain them even after refreshing the page.


# Technologies Used : 
- HTML: For the structure of the application.
- CSS: For styling the app and giving it a clean look.
- JavaScript: To handle the functionality of adding, checking, deleting, and saving tasks in local storage.

# How to Use
Clone or download this repository.
Open the index.html file in a web browser to launch the app.
In the input field, type your task and click the "Add" button to add the task to the list.
Click on a task to mark it as completed.
Click the close (×) button next to a task to delete it.
Tasks will be automatically saved in your browser's local storage.
Project Structure
index.html: The main HTML file containing the structure of the app.
todostyle.css: The CSS file that styles the app.
script.js: The JavaScript file containing logic to handle task addition, deletion, completion, and saving tasks to local storage.
Images: The folder contains the necessary icons and images used in the app.
Local Storage Functionality
The app uses the localStorage API to store tasks locally on the user's browser. When tasks are added, removed, or marked as complete, the app saves the current state to localStorage. When the page is refreshed, the saved tasks are reloaded automatically.

How to Run Locally
Clone the repository:


Copy code
git clone https://github.com/your-username/to-do-list.git
Navigate to the project folder:


Copy code
cd to-do-list
Open the index.html file in your web browser.

Future Enhancements
Add task prioritization (e.g., High, Medium, Low).
Implement task categories (e.g., Work, Personal).
Add due dates and reminders.
Allow users to edit tasks.
License
This project is open-source and available under the MIT License.
