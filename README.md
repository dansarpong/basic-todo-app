# Basic Todo App

This is a simple Todo application built using Docker for practice purposes.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/basic-todo-app.git
    cd basic-todo-app
    ```

2. Build and run the application using Docker Compose:
    ```sh
    docker build . -t basic-todo-app
    docker run -p 3000:3000 basic-todo-app
    ```

3. Open your browser and navigate to `http://localhost:3000` to see the app in action.

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
