# ChatHaven

Welcome to ChatHaven, a dynamic and interactive chat application built with Django. ChatHaven allows users to create and join chat rooms, participate in discussions, and connect with others based on shared topics of interest.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Features Implemented](#features-implemented)
- [How It Was Developed](#how-it-was-developed)
- [What It Does](#what-it-does)
- [Usage](#usage)
- [Requirements](#requirements)

## Introduction

ChatHaven is a full-featured chat application designed to provide a seamless and engaging user experience. It leverages Django's robust backend capabilities and integrates REST API for efficient communication between the frontend and backend. The application supports user authentication, chat room creation, and message posting, making it a versatile platform for online communication.

## Technologies Used

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite
- **Other Libraries**: Pillow, CORS Headers

## Features Implemented

- **User Authentication**: Register, login, and logout functionalities.
- **Chat Rooms**: Create, update, and delete chat rooms.
- **Messaging**: Post messages in chat rooms, view message history.
- **User Profiles**: View and update user profiles with avatars.
- **REST API**: Access chat rooms and messages via API endpoints.

## How It Was Developed

ChatHaven was developed using Django's powerful features for rapid web development. The application follows the MVC (Model-View-Controller) architecture, ensuring a clean separation of concerns. The REST API endpoints are built using Django REST Framework, facilitating smooth data exchange between the frontend and backend.

## What It Does

ChatHaven allows users to:

- Register and create an account
- Log in and access the chat functionality
- Create new chat rooms based on various topics
- Post and read messages in chat rooms
- View and update their profile information

## Usage

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/chathaven.git
   cd chathaven
   ```

2. **Install the dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the server**:
   ```sh
   python manage.py runserver
   ```

4. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:8000/`.

## Requirements

- Python 
- Django 
- Django REST Framework
- SQLite
- Pillow 
- Django CORS Headers

---
