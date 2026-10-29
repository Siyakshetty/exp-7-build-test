# Experiment 11: Containerizing a Python Application Using Docker

## Aim
To containerize and execute a Python application using Docker.

## Files
- app.py: Python program that adds two numbers.
- Dockerfile: Instructions to build the Docker image.
- README.md: Documentation for the experiment.

## Procedure
1. Build the image using `docker build -t python-app .`
2. Run the container using `docker run --name python-container python-app`.
3. Verify the container using `docker ps -a`.
4. View output using `docker logs python-container`.

## Expected Output
Welcome to Docker Lab!
Python application is running inside a container.
First number: 10
Second number: 20
Sum: 30

## Result
The Python application was successfully containerized and executed using Docker.
