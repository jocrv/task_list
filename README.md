# Task Manager

A simple Java console application to manage a list of tasks. Users can add, view, and remove tasks.

## Features

- Add a task
- View all tasks
- Remove a task
- Exit the application

## Prerequisites

- Java Development Kit (JDK) installed

## Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/TaskManager.git
    cd TaskManager
    ```

2. Compile the Java application:

    ```sh
    javac TaskManager.java
    ```

3. Run the application:

    ```sh
    java TaskManager
    ```

## Application Usage

The console application will prompt you with a menu to:

1. **Add a task**: Enter a description for the task to add it to the list.
2. **View all tasks**: Display all tasks currently in the list.
3. **Remove a task**: Enter the task number to remove it from the list.
4. **Exit the application**: Close the application.

### Example Interaction

```plaintext
Task Manager
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 1
Enter task description: Buy groceries
Task added.

Task Manager
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 2
Tasks:
1. Buy groceries

Task Manager
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 3
Enter task number to remove: 1
Task removed.

Task Manager
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 4
Exiting...

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.



Replace `jocrv` in the clone URL with your GitHub username. This `README.md` provides instructions on how to set up and use the Task Manager application, as well as an example interaction to illustrate how the application works.
