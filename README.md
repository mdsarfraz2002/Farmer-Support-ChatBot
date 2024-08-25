# Farmer Support ChatBot

Welcome to the "Farmer Support ChatBot" project! This repository focuses on developing a chatbot tailored for farmers, equipped with features such as language translation, speech recognition, and real-time communication. The project integrates a Flask backend and a React frontend, creating an interactive platform for farmers to seek information and assistance.

![Screenshot 2024-01-13 at 3 30 24 PM](https://github.com/adil200/Farmer-Support-ChatBot/assets/75264739/5dcf78d5-e627-4b6f-9174-56ea06431021)

## Overview

In this repository, you'll find a Flask backend (`chat.py`), a React frontend (`app.jsx`), and training scripts (`train.py`) for the machine learning model. The machine learning model is trained on agricultural intents to provide context-aware responses. The frontend offers an intuitive chat interface, supporting multiple languages and enhancing user interaction.

## Installation

To run the project using Docker Compose, follow the steps below:

# Prerequisites
Ensure you have Docker and Docker Compose installed on your machine. You can install Docker and Docker Compose.

## Running the Application

# Clone the Repository:
```bash
 git clone https://github.com/adil200/Farmer-Support-ChatBot.git
 cd Farmer-Support-ChatBot
```
# Build and Run the Containers:
In the project directory, run the following command to build and start the services:
```bash
 docker-compose up --build
```
This command will:

Build the Docker images for both the backend and frontend.
Start the Flask backend on port 5000.
Start the React frontend on port 5173.

# Access the Application:
Once the containers are up and running, you can access the application by navigating to:

Frontend: http://localhost:5173
Backend: http://localhost:5000

## Features

- Language Translation: The chatbot supports multiple languages for user convenience.
- Speech Recognition: Users can interact with the chatbot using voice commands.
- Real-time Communication: Utilizes Socket IO for seamless real-time communication.
- Dockerization: The application is containerized using Docker for easy deployment and scaling.

## Acknowledgments

This collaborative effort is led by a dedicated team of four individuals:

- **N Adil**
- **Ananya S M**
- **Kavya Kartik**

This project is a capstone project developed as a final-year project. The Farmer Support ChatBot aims to assist farmers by providing real-time solutions and advice on various farming issues. It leverages AI and machine learning to provide accurate and timely responses. Various tutorials and resources on chatbot development, language translation, and real-time communication inspire the code and techniques used in this project.
