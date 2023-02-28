# plotly-tutorial
This Jupyter Notebook condenses the Plotly API into one easy to use document with examples.  Tutorial for https://www.youtube.com/watch?v=GGL6U0k8WYA


# Getting Started

### Install Python
[Installation Documentation](https://www.python.org/downloads/)
```
brew install python
```

### Create Virtual Environment
From the project root directory open a terminal in VSCode & run:

Windows:
```                          # If this is not your working directory in VS Code
# python -m venv src/venv            # If not already made
src/venv/Scripts/activate.bat        # using cmd terminal
# src/venv/Scripts/activate          # powershell only
pip install -r requirements.txt
```


Mac:
```
# python3 -m venv src/venv
source src/venv/bin/activate
pip3 install -r requirements.txt
```


## Running Locally

### Select Python Interpreter
[Documentation](https://code.visualstudio.com/docs/python/environments)

In VSCode you can select the python interpreter associated with the virtual environment that was created
above. On a mac you can use (command + shift + p), or windows (ctrl + shirt + p) which will pop up an input
for VSCode commands. From there you can type in "Python: Select Interpreter", once selected it will give you
the option to select an interpreter to use for the project.  You should choose the one in the virtual environment (i.e., src/venv/bin/python3).

### Windows Select Default Shell
[Documentation](https://stackoverflow.com/questions/44435697/vscode-change-default-terminal#:~:text=You%20can%20also%20select%20your,selecting%20Terminal%3A%20Select%20Default%20Shell.)

If you're on Windows there can be some trouble when activating the virtual environment depending on
the shell used.  It is recommended to move away from Powershell in favor of CMD.


### Start Notebook
```
# pip install --pre jupyterlab
jupyter-lab
```
