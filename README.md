# GenAI---Containerize-your-app

Dockerized Generative AI Application

This project demonstrates how to containerize a Python-based Generative AI (GenAI) application using Docker. The application leverages technologies like LangChain, Streamlit, Neo4j, and Ollama to allow querying of PDF files with a natural language interface.

Table of Contents
Introduction
Prerequisites
Installation Guide
Dockerizing the GenAI Application
Running the Application
Setting Up Neo4j and LLM Service
Next Steps
Troubleshooting
Introduction
This project provides an easy-to-follow guide for containerizing and deploying a Python-based Generative AI application. The objective is to demonstrate the use of Docker for consistent and portable deployment across different environments, enhancing the accessibility and ease of deployment of AI applications.

Key Features
Docker containerization for consistent deployment
Integration with LangChain for orchestration
Using Neo4j as a vector database
Streamlit for the front-end interface
Integration with Ollama or an alternative LLM service for advanced natural language processing
Prerequisites
Before you begin, ensure you have the following prerequisites installed on your system:

Docker Desktop or Docker Engine (with GPU support if needed)
Git (to clone the repository)
Neo4j (for vector storage)
A Large Language Model (LLM) service such as Ollama (or OpenAI API as an alternative)
Ensure your machine meets the following hardware requirements for optimal performance:

Memory: At least 9.5 GB of available RAM (4.3 GB may not be sufficient).
GPU support if using Docker Desktop on Windows with WSL2 or Docker Engine on Linux.
