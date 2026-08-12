# CodeAlpha Docker Task 4 🐳

This project is completed as part of the **CodeAlpha Internship – Docker Task 4**.

## 📌 Project Overview

The objective of this task is to understand the basics of **Docker containerization** by creating a Docker image for a simple web application and running it inside a Docker container.

The project uses a simple HTML webpage and a `Dockerfile` to demonstrate how an application can be packaged and deployed using Docker.

## 🛠️ Technologies Used

* HTML
* Docker
* Dockerfile
* Docker Container
* Git & GitHub

## 📂 Project Structure

```text
CodeAlpha_Docker_Task4/
│
├── Dockerfile
├── index.html
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/devbhatt0239-sudo/CodeAlpha_Docker_Task4
```

### 2. Navigate to the project directory

```bash
cd CodeAlpha_Docker_Task4
```

### 3. Build the Docker image

```bash
docker build -t codealpha-docker-task4 .
```

### 4. Run the Docker container

```bash
docker run -d -p 8080:80 codealpha-docker-task4
```

### 5. Open the application

Open your browser and visit:

```text
http://localhost:8080
```

## 🎯 Learning Objectives

Through this task, I learned how to:

* Create a Dockerfile
* Build a Docker image
* Create and run a Docker container
* Serve a web application using Docker
* Map container ports to the host machine
* Use Git and GitHub for project version control

## 📸 Project Output

The Dockerized web application can be accessed through the browser after successfully running the container.

## 👨‍💻 Author

**Dev Bhatt**

CodeAlpha Internship – Docker Task 4

## 📜 License

This project was created for educational and internship purposes.
