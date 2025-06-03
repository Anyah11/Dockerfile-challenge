# Dockerfile Challenge

This is a solution to the [roadmap.sh Dockerfile challenge](https://roadmap.sh/projects/basic-dockerfile) that involves creating a basic Docker image. When the container runs, it prints a message to the console and exits.

## 🐳 Objective

Create a `Dockerfile` that prints the message:


## 📄 Requirements

- The file must be named `Dockerfile`.
- It should be placed in the root directory of the project.
- The base image must be `alpine:latest`.
- The container should print **"Hello, [your name]!"** and exit.

## 🚀 How to Use

### 1. Build the Docker Image with Your Name

```bash
docker build --build-arg NAME=Kelechi -t hello-name .
```

### 2. Run the Docker Container
```bash
docker run hello-name
```

#### ✅ Expected Output
```bash
Hello, Kelechi!
```

