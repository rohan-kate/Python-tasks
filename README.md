🐍 Python Projects
Below are 4 different projects created with Python to increase my skills. These cover multiple different aspects such as calculations, password security, API usage, database usage, GUI and networking.

The projects are split between beginner and advanced versions.
---
 📌 Projects
| No. | Project | Description | Key Concepts |
| --- | --- | --- | --- |
| 1 | BMI Calculator | Calculates Body Mass Index, and shows history. | Python, Tkinter, SQLite |
| 2 | Random Password Generator | Generates random passwords depending on user inputs. | Python, secrets, Tkinter |

| 3 | Weather Application | Gets the current weather and forecast. | Python, REST API, Tkinter |
| 4 | Chat Application | Enables users to communicate using a client/server system. | Python, Socket Programming, SQLite |
---
📂 Folder Structure
```text
python_projects/
│
├── README.md
│
├── task2_bmi_calculator/
│   ├── bmi_cli.py
│   ├── bmi_gui.py
│   ├── bmi_core.py
│   ├── test_bmi.py
│   ├── requirements.txt
│   ├── README.md
│   └── DOCUMENTATION.md
│
├── task3_password_generator/
│   ├── password_cli.py
│   ├── password_gui.py
│   ├── pwgen_core.py
│   ├── test_pwgen.py
│   ├── requirements.txt
│   ├── README.md
│   └── DOCUMENTATION.md
│
├── task4_weather_app/
│   ├── weather_cli.py
│   ├── weather_gui.py
│   ├── weather_core.py
│   ├── test_weather.py
│   ├── requirements.txt
│   ├── README.md
│   └── DOCUMENTATION.md
│
└── task5_chat_app/
├── beginner/
│   ├── server.py
│   ├── client.py
│   └── test_beginner.py
│
├── advanced/
│   ├── chat_server.py
│   ├── chat_client.py
│   ├── chat_net.py
│   ├── emoji_map.py
│   └── test_chat.py
│
├── README.md
└── DOCUMENTATION.md
```
🚀 Project Details
1. BMI Calculator
A simple Python application to calculate your Body Mass Index based on your height and weight. It makes understanding what BMI means easier, and also provides a history of previous calculations.
Features
- Calculate BMI using weight and height.
- Shows BMI value and general health category.
- Command line.
- Desktop using Tkinter.
- History of calculations stored using SQLite.
- See previous calculations.
- Chart showing BMI trends.
Technologies
- Python
- Tkinter
- SQLite
- Matplotlib
How to run
```bash
cd task2_bmi_calculator
python -m pip install -r requirements.txt
python bmi_cli.py
```
To run the desktop version:
```bash
python bmi_gui.py
```
---
2. Random Password Generator
A password generator that generates random passwords based on how long the user wants the password and what characters they want included.
Features
- Generate random passwords.
- Choose length of password.
- Uppercase and lowercase letters.
- Numbers and special characters.
- No confusing characters.
- Gives rough idea of password strength.
- Passwords can be copied to clipboard from the GUI.
Technologies
- Python
- Tkinter
- Secrets Module
- Pyperclip (Optional)
How to run
```bash
cd task3_password_generator
python -m pip install -r requirements.txt
python password_cli.py
```
To run the desktop version:
```bash
python password_gui.py
```
---
3. Weather Application
A Python application that uses the OpenWeatherMap API to get weather information. The user can enter a city name to see the current weather and any forecast information.
Features
- Search for weather using city name or supported ZIP code.
- Current temperature.
- Weather conditions.
- Humidity and Wind Speed.
- Forecast information shown on desktop.
- Temperature units can be chosen from GUI.
- Handles API and network errors.
Technologies
- Python
- Tkinter
- REST API
- OpenWeatherMap
- Requests
Setup
1. Create an account at [OpenWeatherMap](https://openweathermap.org/)
2. Create an API key.
3. Install packages.
4. Enter the API key.
Command Prompt (Windows):
```bash
cd task4_weather_app
python -m pip install -r requirements.txt
set OPENWEATHER_API_KEY=your_api_key_here
```
How to run
```bash
python weather_cli.py
```
To run the desktop version:
```bash
python weather_gui.py
```
Make sure to keep your API key private and do not upload to a public GitHub repo.
---
4. Chat Application

A client/server messaging application using Python socket programming. This shows how multiple clients can connect to a server and send messages.
There are two versions of this project, one for beginners and one for advanced.
### Beginner Version
Features
- Client/server.
- Send and receive messages.
- Connect multiple chat clients (up to the limit).
- Username.
- Simple command line.
How to run
Open 1st terminal:
```bash
cd task5_chat_app/beginner
python server.py
```
Open another terminal:
```bash
cd task5_chat_app/beginner
python client.py
```
Open more clients if needed.
 Advanced Version
Features
- Desktop application.
- Sign up and log in.
- Multiple chat rooms.
- Messages sent in real time.
- Messages saved locally using SQLite.
- Passwords hashed.
- Optional notifications on desktop.
How to run
Run the server first:
```bash
cd task5_chat_app/advanced
python chat_server.py
```
Open another terminal and run the client:
```bash
cd task5_chat_app/advanced
python chat_client.py
```
Open more clients for multiple users.
Technologies
- Python
- Socket Programming
- Tkinter
- SQLite
- Threading
---
🛠️ Installing
Ensure you have:
- Python 3.10 or higher version.
- Visual Studio Code or another Python editor.
- Command Prompt or terminal.
- Internet connection (for weather application).
- OpenWeatherMap API key.
Check python is installed:
```bash
python --version
```
Install packages in each project folder:
```bash
python -m pip install -r requirements.txt
```
Not all projects will use 3rd party packages as much as possible built in modules are used.
---
🧪 Testing
Each project has testing files to test key aspects.
Run tests in relevant project folder:
BMI Calculator
```bash
python -m unittest -v
```
Password Generator
```bash
python -m unittest -v
```
Weather Application
```bash
python -m unittest -v
```
Chat Application (Beginner)
```bash
cd task5_chat_app/beginner
python -m unittest -v
```
Chat Application (Advanced)
```bash
cd task5_chat_app/advanced
python -m unittest -v
```
---
🎯 What I learnt
I was able to look into and practice:
- Python basics and OOP.
- Functions, modules and exceptions.
- Creating GUIs using Tkinter.
- Using databases with SQLite.
- Using APIs and JSON data.
- Generating secure random passwords.
- Client/server.
- Socket programming and threading.
- Creating and running simple unit tests.
- Splitting Python projects into modules.
---
🔮 Possible Improvements
Possible improvements for future versions:
- More advanced BMI reports and charts.
- More security for passwords.
- More advanced weather charts and locations.
- File sharing and better chat notifications.
- Improve UI.
- More automated testing and deployment options.
---
⚠️ Notes
- Weather Application needs a valid API key from OpenWeatherMap.
- Chat Application is for learning purposes only and messages will not be secure.
- BMI Calculations are general information only.
- Do not put passwords, API keys or any private information in public repos.
---
👨‍💻 About
This repository contains 4 Python projects that were created to help with practical learning. My aim was to learn how to create useful applications using Python, using external services, databases and connecting multiple users.

If you found these projects useful please take a look at the code and learn from them. Please also suggest any improvements.
---

Thank you for visiting this repository! ⭐
