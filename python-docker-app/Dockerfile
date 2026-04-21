# Use an official Python runtime as a parent image
FROM python:3.11-slim

#set working directory
WORKDIR /app

#moves your app.py file to the container
COPY . . 

#run when container starts
CMD ["python", "app.py"]