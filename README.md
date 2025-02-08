# Task Master Pro

Welcome to Task Scheduler, a comprehensive Java application designed to manage tasks efficiently. 

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


## Introduction

Task Master Pro is a task management application built using Java. It provides a robust set of features to help users create, manage, and track tasks. This project aims to demonstrate best practices in Java development, including project structure, coding standards, and documentation.

## Features

- Create, update, and delete tasks
- Mark tasks as complete or incomplete
- User authentication and authorization

## Installation

### Prerequisites

- Java Development Kit (JDK) 17 or later
- Apache Maven 3.6.0 or later
- A database (H2)

### Steps

1. Clone the repository:

    ```sh
    git clone https://github.com/dushf12/App_task_scheduler.git
    cd App_task_scheduler

    ```

2. Configure the database:

    Update the `application.properties` file with your database configuration.

3. Build the project:

    ```sh
    mvn clean install
    ```

4. Run the application:

    ```sh
    mvn spring-boot:run
    ```

## Usage

Once the application is running, you can access it at `http://localhost:8080`. You can use the web interface to manage your tasks.

### Endpoints

- `/tasks` - View and manage tasks
- `/tasks/{id}` - View, update, or delete a specific task
- `/login` - User login
- `/register` - User registration


