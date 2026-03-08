## DrawMate - 🎨 Generative Drawing Agent

A simple Python agent that converts natural language prompts into Turtle graphics drawings.

The program reads a prompt like:

draw a house with sun

and generates a Python Turtle script that draws the picture automatically.

---

## 🚀 Features

* Converts text prompts into drawings
* Uses Python Turtle graphics
* Generates a new Python file for each drawing
* Simple rule-based drawing agent

---

## 📦 Requirements

* Python 3.x
* Turtle (included with Python)

---

## ▶ How to Run

1. Clone the repository

git clone https://github.com/Jananiselvakumar/drawing-agent.git

cd drawing-agent

2. Run the drawing agent

python drawing_agent.py

3. Enter a prompt when asked

Example:

Prompt ▸ draw a house with sun

4. The program will generate a file like:

draw_20260308_210312.py

5. Run the generated file

python draw_20260308_210312.py

A Turtle graphics window will open and draw the scene.

---

## ✏ Example Prompts

draw a house with sun
draw a heart
draw sun and write "Hello"
draw a house and write "Welcome"

---

## 📁 Project Structure

drawing-agent

drawing_agent.py
README.md

---

## 🧠 How It Works

The agent reads the prompt and checks for keywords like:

* sun
* house
* heart
* text

Based on the keywords, it generates Turtle drawing commands and saves them in a new Python file.

---

## 🔮 Future Improvements

* Add support for trees and mountains
* Build a GUI interface
* Add AI prompt understanding
* Improve drawing styles
