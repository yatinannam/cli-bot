# CLI Bot
[![PyPI version](https://badge.fury.io/py/cli-botx.svg)](https://pypi.org/project/cli-botx/)

A simple **command-line assistant built with Python**, designed to perform everyday tasks directly from the terminal — from opening websites and searching Google to managing tasks and doing quick calculations.

---

## Features

- Greet the bot with basic commands
- Show current date and time
- Open commonly used websites:
- Google, YouTube, GitHub, LinkedIn, ChatGPT, Wikipedia, Reddit, Gemini, Perplexity
- Perform Google searches directly from the terminal
- Calculator for quick math expressions
- To-Do List management:
  - Add tasks
  - View all tasks
  - Mark tasks as done
  - Clear all tasks

---

## Tech Stack

- **Language:** Python 3.8+
- **Standard Libraries Used:**  
  `datetime`, `os`, `ast`, `webbrowser`, `urllib`, `random`, `operator`

---

## Installation

You can install the package directly from **PyPI**: [https://pypi.org/project/cli-botx](https://pypi.org/project/cli-botx)

```bash
pip install cli-botx
```

---

## Usage

Run from the terminal
Once installed, simply type:

```bash
  cli-botx
```

Or run locally
If running the script directly from source:

```bash
python bot.py
```

Or import it into another Python file

```bash
from cli_bot import main
main()
```

---

## Available Commands

| Command             | Description                                                                                        |
| ------------------- | -------------------------------------------------------------------------------------------------- |
| `hello`             | Greet the bot                                                                                      |
| `time`              | Show current time and date                                                                         |
| `open <site>`       | Open Google, YouTube, GitHub, Reddit, Wikipedia, LinkedIn, Twitter, ChatGPT, Gemini, or Perplexity |
| `search <query>`    | Perform a Google search                                                                            |
| `calc <expression>` | Evaluate math (e.g., `calc 2+3*4`)                                                                 |
| `add <task>`        | Add a task to the to-do list                                                                       |
| `list`              | Show all current tasks                                                                             |
| `done <num>`        | Mark a task as completed                                                                           |
| `clear`             | Remove all tasks                                                                                   |
| `help`              | Show help menu                                                                                     |
| `exit`              | Quit the bot                                                                                       |

---

## Project Structure

```bash
cli-bot/
│
├── cli_bot/
│   ├── __init__.py
│   └── bot.py
│
├── LICENSE
├── README.md
├── setup.py
└── tasks.txt   # Auto-created when tasks are added
```

---

## Developer Setup

To install locally for development or contribution:

```bash
git clone https://github.com/yatinannam/cli-bot.git
cd cli-bot
pip install -e .
```

Then run

```bash
cli-botx
```

---

## Contributing

Contributions are welcome!
If you'd like to add new features, improve the code, or fix issues:

```bash
# 1. Fork the repository

# 2. Create a new branch
git checkout -b feature-name

# 3. Commit your changes
git commit -m "Add feature-name"

# 4. Push to your branch
git push origin feature-name

# 5. Open a Pull Request
```
---
