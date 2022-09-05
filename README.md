# ManimCE
Initializing GitHub Repository with Manim Code for completed tutorials

# Instructions for Starting Process

## Clone Repo From GitHub
gh repo clone bcusack91/ManimCE

## Create Virtual Environment
python -m venv venv

## Install Manim with Pip
python -m pip install manim

## Initialize Manim Folder
manim init project project

## Open vs code
code .

## Select Interpreter using Command Line Palette
Select Python Interpreter from within virtual environment (should be recommended)

## Navigate to Project Folder and Running Manim to create circle
cd project
manim -pql scene.py CreateCircle
