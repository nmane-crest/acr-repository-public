# Use an official Python runtime as a parent image (you can change this to any other base image you need)
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Expose port 80 for the container (optional, adjust if needed)
EXPOSE 80

# Define environment variables (optional, you can change it as needed)
ENV NAME World

# Run a simple Python command for testing (this can be replaced with your actual application)
CMD ["python", "-c", "print('Hello, World!')"]
