# Random Advice Generator

A simple desktop application built with Python and Tkinter that fetches random advice from a public API and displays it in a user-friendly graphical interface.

## Features

- Get random advice with a single click
- Simple and clean Tkinter GUI
- Uses a public Advice API
- Handles internet connection errors gracefully
- Lightweight and beginner-friendly project

## Technologies Used

- Python
- Tkinter
- Requests
- Advice Slip API

## Project Structure


01_Advice_Generator/
│
├── advisor.py
└── README.md


## Installation

Install the required package:

bash
pip install requests


## Run the Project

bash
python advisor.py


## How It Works

1. The application sends a request to the Advice Slip API.
2. A random piece of advice is returned.
3. The advice is displayed inside the application window.
4. Clicking the Get Advice button fetches a new random advice.

## API Used

Advice Slip API

https://api.adviceslip.com/advice

## Learning Goals

This project was created to practice:

- Working with APIs
- Sending HTTP requests using Requests
- Error handling with try-except
- GUI development with Tkinter
- Displaying dynamic data in desktop applications

## Preview

A desktop window containing a text area that displays random advice and a button for generating new advice.