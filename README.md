<label id="top"></label>

<div align="center">
  <img src="./images/mek.jpg" width="150" />
  <img src="./images/original.png" width="150" />

  <h1>Mek's GitHub Repository</h1>
  <h3>Creator & Maintainer of Onyx</h3>
</div>

---

### Table of Contents

- [Introduction](#introduction)
- [A Little About Me](#a-little-about-me)
- [About My Journey](#about-my-journey)
- [What Am I Currently Doing?](#what-am-i-currently-doing)
- [Projects](#projects)
- [Issues](#issues)

---

### Introduction

Welcome to my GitHub! This repository serves as a central hub for all my current/released applications, portfolio applications and a glimpse into my journey as a developer. Thanks for stopping by!

[<a href="#top">Top</a>]

---

#### A Little About Me

I currently study UI/UX development in my freetime. Client-side has always been my *leaned-on* favorite thing to do. I have studied other languages and can work in bash scripts along with python automation and task loop events. As of today, I have:

  - 7+ years in [Python](https://python.org)
  - 4+ years in [JavaScript](https://nodejs.org)
  - 3+ years in [Markdown](https://www.markdownguide.org/basic-syntax/)
  - 1+ years in [Bash](https://www.geeksforgeeks.org/bash-scripting-introduction-to-bash-and-bash-scripting/)
  - < 1 year in [C#](https://learn.microsoft.com/en-us/dotnet/csharp/)

[<a href="#top">Top</a>]

---

#### About My Journey

I started my journey back in 2016-2017 with my best friend. I originally wanted to learn Java as we were both avid Minecraft players and I wanted to help in developing mods. After my first or second go-round with attempting to build a calculator, I moreso gave up. About a year later, we were hanging out and I was watching my friend play around with machine learning by having a car go around a track and teach itself to drive around said track. This re-peaked my interest in development and thus we conversed about a language and decided on Python. Python is my mother language and I enjoy using it very much. It's very easy to understand and after spending a few hours going over some basics, I decided I was smart enough to start building a [Discord Bot using Disnake.py](https://docs.disnake.dev/en/stable/index.html). I was very wrong and it took months for me to grasp that concept. However, now I am able to do quite a lot.

[<a href="#top">Top</a>]

---

#### What Am I Currently Doing?

I have recently shifted my focus back into a Python lifestyle. In the coming months, I'll be converting most of my applications here on my repo to a python based language and framework. I have chosen to start my proficiencies in:

- [Click](https://click.palletsprojects.com/en/stable/) is *"a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. It’s the “Command Line Interface Creation Kit”. It’s highly configurable but comes with sensible defaults out of the box."*
- [Rich](https://rich.readthedocs.io/en/stable/) is *"a Python library for writing rich text (with color and style) to the terminal, and for displaying advanced content such as tables, markdown, and syntax highlighted code."*
- [Textual](https://textual.textualize.io/tutorial/) is *"is a Rapid Application Development framework for Python, built by Textualize.io to build sophisticated user interfaces with a simple Python API. Run your apps in the terminal or a web browser!"*
- [PySide6](https://doc.qt.io/qtforpython-6/gettingstarted.html#getting-started) is a framework that *"provides Python bindings for the Qt application framework, enabling you to develop full-featured, cross-platform GUI applications with a modern user interface."*
- [Flask](https://flask.palletsprojects.com/en/stable/) is *"a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications."*

Between the list above of selected frameworks to point my focus towards, I have elected to begin with three: Click, Textual, and PySide6. I have previous experience working with PySide6 so I've decided to start building my projects out in the following manner

This layout will use a ToDo application for the example

```
todo/
| - cli/ -> the click application
| - core/ -> all logic layer interactions with the applications' data and ui layers
| - config/ -> handles loading in application settings and file structure requirements for run-time
| - console/ -> the textual application
| - desktop/ -> the pyside6 application
| - mobile/ -> the expo go application
| - web/ -> the web app using react

> NOTE: the mobile and web versions are built using the expo go and tauri/reactjs frameworks. These are JavaScript frameworks and are better to use in these environments
```

<b><u>What's The Purpose?</u></b>

Although I have experience in a few languages, scripting or other, I am always learning. Practicing new concepts, learning new ideas, etc. This repository serves as the path of my journey, showcasing what I've learned and what I'm most proud of.

[<a href="#top">Top</a>]

---

### Projects

> NOTE: At this time, I am still attempting to understand packaging applications down into appropriate executables for my apps. All apps are FOSS and will need to be ran open-source on your system. Please see [How To Install & Run](#how-to-install--run)

- Automation
  - TBA
- Desktop Apps
  - Task Manager - https://github.com/mek0124/task-manager
    - A Textual console application for efficient task trackig implementation
  - Mek's Book Review - https://github.com/mek0124/meks-book-review
    - A PySide6 self-hosted FOSS application for reviewing books you've read
- Games
  - Number Guess - https://github.com/mek0124/number-guess
    - A PySide6 desktop application for guessing a number 1-100
- Mobile Apps
  - TBA
- Scripts
  - TBA
- Web Apps
  - TBA

[<a href="#top">Top</a>]

---

### How To Install & Run

1. Clone the repository
  - `git clone https://github.com/mek0124/repo_name_here`
2. cd into the project, and install dependencies
  - `cd repo_name_here`
  - `pip install -r requirements.txt`
3. Run the application
  - `python3 main.py`

[<a href="#top">Top</a>]

---

### Issues

If at anytime you come into any issues, please create a new issue on the corresponding repo's issues page.

[<a href="#top">Top</a>]
