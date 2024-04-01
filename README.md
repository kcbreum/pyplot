# Web Mining & Applied NLP Project 3 - Employ Matplotlib, pyplot and Engage

## Project Description
This project is used to reinfoce key Python visualization skills through practice of web-enabled Jupyter notebooks. It utilizes Matplotlib library, including the pyplot module.

## Project Setup
### Create a virtual Environment
``` shell
py -m venv .venv
py -m .\.venv\Scripts\activate
```

### Install Dependencies and Upgrade Pip
``` shell
py -m pip install jupyterlab
py -m pip install matplotlib
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
```

### Freeze Requirements
``` shell
py -m pip freeze > requirements.txt
```

### Add to .gitignore
``` shell
.venv/
.vscode/
*~
.ipynb_checkpoints/
*.ipynb_meta/
```

## Dependencies Imported
``` shell
from collections import Counter
from random import randint
import matplotlib.pyplot as plt
```

## Git Add and Commit
``` shell
git add .
git commit -m "update message goes here"
git push origin master
```

## Credentials
This was a required project to be completed for the MS in Data Analytics degree at Northwest Missouri State University. Assisted instructions were given by Denise Case. Additionally AI was utilized to complete this project.
Deitel, P. (2021). *INTRO TO PYTHON FOR COMPUTER SCIENCE AND DATA SCIENCE : learning to program with ai, big data, and the cloud*, global edition. Pearson Education Limited.