# Dockerized Web Application

This project demonstrates how to containerize a simple Python Flask web application using Docker.
The goal of this project is to ensure consistent application deployment across different environments.

---

## 🚀 Project Overview

- Built a simple Flask-based web application
- Created a Dockerfile to containerize the application
- Built a Docker image and ran it as a container
- Exposed the application using port mapping

---

## 🛠️ Tech Stack

- Python
- Flask
- Docker
- Linux

---

## 📁 Project Structure

docker-web-app/
│── app.py
│── requirements.txt
│── Dockerfile
│── README.md

---

## 🐳 Dockerfile Explanation

- **Base Image:** `python:3.9-slim`
- **Working Directory:** `/app`
- **Dependencies:** Installed using `requirements.txt`
- **Port:** Application runs on port `5000`
- **Command:** Starts the Flask application
