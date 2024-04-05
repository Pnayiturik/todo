# My Todo App

A simple web-based Todo App that allows users to manage their tasks.
## How to access my app
-Make sure Docker is installed on your machine. 
Pull the Docker image: docker pull pnayiturik/todo-app 
Run a container using the image: docker run -p 8080:80  pnayiturik/todo-app 
Open your web browser and go to http://localhost:8080 to view the application running inside the Docker container.
## Usage
1. Add a new task:
- Enter the task name in the input field.
- Click the "Add Todo" button.
2. View your tasks:
- The list of tasks will be displayed below.
- Each task shows its name and status (completed or not done).
3. Mark a task as completed:
- Click the checkbox next to the task.
4. Delete a task:
- Click the "Delete" button next to the task.

## Features
- Add new tasks.
- Mark tasks as completed.
- Delete tasks.
- Responsive design for various screen sizes.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

## Assumptions and Decisions
-During the development process, the following assumptions and decisions were made: 
1. **Styling**: Basic styling is provided using CSS. You can make additional styling and design improvements as needed.
2. **Framework/Libraries**: The application was developed using pure HTML, CSS, and JavaScript without using any frameworks or libraries to keep it lightweight and simple.
3. **Docker Image**: The Docker image is based on the N.G.I.N.X. Alpine image serving static files. This was chosen for its lightweight nature and suitability for hosting front-end applications.
4. **Port Mapping**: When running the Docker container, port 8080 on the host is mapped to port 80 on the container. This can be adjusted as needed depending on the host environment.
