# CALMCONNECT: AI-POWERED THERAPY WITH DJANGO AND LLAMA 3

# Introduction

In today's fast-paced world, mental health support needs to be accessible, reliable, and adaptable. Many people hesitate to seek therapy due to stigma, costs, or scheduling conflicts. CalmConnect bridges this gap by offering an AI-powered chatbot that provides instant emotional support while also allowing users to transition to a human therapist when needed.

Built with Django and powered by Meta's Llama 3 model, CalmConnect ensures a smooth and engaging therapy-like experience. The AI chatbot provides helpful insights, active listening, and coping strategies, while the platform offers an easy way to escalate the conversation to a licensed therapist.

# Features
🧠 AI-Powered Chatbot – Chat with an intelligent assistant powered by Llama 3.

🎯 Seamless Therapist Connection – Click "Chat with a Therapist" to be connected to an available professional.

🔒 Secure Django Backend – Manages authentication, AI responses, and therapist availability.

# Technology Stack

# Component	Technology Used

Backend	Django: Python, Llama 3 (via Ollama)

Frontend: HTML, CSS, JavaScript

Database: PostgreSQL (or SQLite for development)

# Installation Guide

# Clone the Repository

git clone https://github.com/rillhancho/Therapy-Chatbot.git

cd Therapy-Chatbot

# Create a Virtual Environment

python -m venv venv

source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependancies

pip install -r requirements.txt

# Run Migrations

python manage.py migrate

# Start the django server

python manage.py runserver

# Run Ollama for Llama 3 Integration

ollama run llama3

# Access the web application

Open http://127.0.0.1:8000/ in your browser.




