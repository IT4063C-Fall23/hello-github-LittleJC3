# Python Exercises

The instructions for this assignment can be found at [https://it4063c.github.io/assignments/python-exercises](https://it4063c.github.io/assignments/python-exercises)

**Objectives**
- Refresher on Python and some common libraries such as `numpy`.
- Refresher on Jupyter Notebooks.
- Introduction/Re-introduction to using git and GitHub.


**Emojis Legend**
- 👨🏻‍💻 - Instructions; Tells you about something specific you need to do.
- 🦉 - Tips; Will tell you about some hints, tips and best practices
- 📜 - Documentations; provides links to documentations
- 🚩 - Checkpoint; marks a good spot for you to commit your code to git
- 🕵️ - Tester; Don't modify code blocks starting with this emoji

## Installing Dependencies
This assignment does not assume any particular setup. To install the dependencies, please run the command relevant to you're setup.
- if you're using `poetry`, run `poetry install`.
- If you're using `pipenv`, run `pipenv install`
- if you're using `pip`, run `pip install -r requirements.txt`

## Running the automated checks
to run all the automated tests 
```bash 
pytest --capture=sys
```

to run the (python exercises) automated test
```bash 
pytest --capture=sys tests/python_test.py
```

to run the (numpy exercises) automated test
```bash 
pytest --capture=sys tests/numpy_test.py
```

## Project Structure
```
.
├── .git                1️⃣  
├── .vscode             2️⃣  
│   ├── extensions.json 
│   └── settings.json   
├── .gitignore          3️⃣  
├── my_story.ipynb      4️⃣  
├── notebook_test.py    5️⃣  
├── README.md           6️⃣  
└── requirements.txt    7️⃣  
```
- 1️⃣ DO NOT TOUCH THIS DIRECTORY. This is what makes your folder a git repo.
- 2️⃣ This directory contains some supporting files for helpful extensions, and VSCode settings 
- 3️⃣ Another git related files. This tells git not to track certain files and folders that you don't want being uploaded
- 4️⃣ That's where the party is. You'll only be working in this file.
- 5️⃣ Some automated tests and checks
- 6️⃣ The README file (this right here)
- 7️⃣ The dependencies needed for this project. Actually deps and deps of deps, ...etc.

## Credits
- The helping emojis idea is inspired by `@kentcdodds` workshops.

------------
## 🤔 Reflection
Examples for how you can reflect on this assignment
* How long did it take you to complete the assignment?
This assignment took me about 5-10 minutes.
* What do you think of this completion time?
I think this is standard for me since I'm accustomed to using Git/GitHub
* With hindsight, what would you do differently getting started with this assignments, now that you know what you know? 
I feel the work was pretty straightforward with nothing to really change. If anything, see if there are other git commands that do similar functions.

## Self-Evaluation:
Out of 20 points for this assignment, I should get .... points
I believe I should get 20/20 points for this assignment. I followed the guidelines and submitted the necessary files/commits