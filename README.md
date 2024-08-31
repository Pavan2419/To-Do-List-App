Too list App
Overview
The Task Manager App is a simple Android application designed to help users manage their tasks efficiently. The app provides a basic interface where users can add new tasks and view a list of their current tasks.

Features
Add New Task: Users can input a new task in the provided EditText field and press the "Add Task" button to add it to the list.
View Tasks: Tasks are displayed in a ListView below the "Add Task" button, allowing users to see their current tasks.
Layout Description
The app's user interface is defined in the activity_main.xml layout file. The layout is structured using a RelativeLayout, and includes:

EditText (editTextTask):

Allows users to enter a new task.
Positioned at the top of the layout with a hint text "Enter new task".
Button (buttonAddTask):

Users press this button to add the entered task to the list.
Positioned directly below the EditText.
ListView (listViewTasks):

Displays the list of tasks that have been added.
Positioned below the "Add Task" button, filling the remaining space of the layout.
Getting Started
To get started with the Task Manager App, clone this repository and open it in Android Studio:

bash
Copy code
git clone https://github.com/your-username/task-manager-app.git
Open the project in Android Studio and run it on an emulator or physical device to see the app in action.

Contributing
Contributions are welcome! If you'd like to contribute to the development of this app, please fork the repository, create a new branch, and submit a pull request with your changes.
