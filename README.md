# 🐍 Python Developer Projects

This repository contains beginner-friendly Python projects that showcase basic functionality for common real-world tasks. Each project is self-contained and demonstrates core programming concepts such as input/output, conditionals, loops, functions, and API integration.

---

## 📁 Projects Overview

### 1. 🧮 Simple CLI Calculator (`calculator.py`)
A command-line calculator that performs basic arithmetic operations: addition, subtraction, multiplication, and division.

**Features:**
- Takes user input for two numbers and desired operation.
- Handles divide-by-zero errors gracefully.

**How to Run:**
```bash
python calculator.py
```

---

### 2. ✅ Task Management App (`to-do-list.py`)
A simple terminal-based to-do list application that lets users manage tasks interactively.

**Features:**
- Add multiple tasks initially
- View, add, update, or delete tasks
- Looping menu until user chooses to exit
- Handles invalid inputs

**How to Run:**
```bash
python to-do-list.py
```

---

### 3. 🌦️ GUI Weather App using OpenWeatherMap API (`weatherapi.py`)
A Python GUI app that shows live weather updates using the OpenWeatherMap API and `Tkinter`.

**Features:**
- GUI-based city input field
- Fetches and displays:
  - Weather condition
  - Temperature (current, min, max)
  - Pressure, humidity, wind speed
  - Sunrise and sunset time

**Requirements:**
- `requests` library
- OpenWeatherMap API key

**How to Run:**
```bash
python weatherapi.py
```

> ⚠️ Replace the `appid` in the script with your own [OpenWeatherMap API key](https://openweathermap.org/api) for production use.

---

## 📦 Installation

If not already available, install the required Python module:

```bash
pip install requests
```

> `Tkinter` usually comes pre-installed with Python, but if not, install it using your OS's package manager.

---

## 📜 License

This repository is under the [MIT License](https://opensource.org/licenses/MIT). Use freely with credit.