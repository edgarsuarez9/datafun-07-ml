# datafun-07-ml

In this assignment, we start by creating a new project in GitHub (for storing and sharing) and on our machine (so we can use our tools). 

## Create Project

Created project in github and Cloned Project down to machine. 

```
# open Powershell

CD Documents 
Git Clone (Repo URL)
```
Opened in VS Code

## Useful .gitignore file 

```
# This .gitignore file lists content that does NOT need to be tracked in the project history

# Python virtual environment
.venv/

# Visual Studio Code settings and workspace
.vscode/
```
## How to Import Dependencies

Create a file in the root folder of your repo (same level as the README.md) named requirements.txt with the following content.

Install the packages listed in the requirements file with this command:
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
scipy

```
py -m pip install -r requirements.txt
```
## Set Python Interpeter
Press Ctrl + Shift + P (or Cmd + Shift + P on macOS) to open the Command Palette.

Select Interpreter: Type Python: Select Interpreter and select it from the list.

Choose the Interpreter: You will see a list of available Python interpreters. Select the one that corresponds to your desired environment (e.g., a virtual environment or a system Python installation). If you’ve created a virtual environment, it should appear in the list.
Check the Status Bar: After selecting the interpreter, you should see the Python version displayed in the status bar at the bottom left of the window.

Open a Terminal: You can open a terminal in VS Code (Ctrl + ``) and type python -m pip list` to confirm that your installed packages are available.

## Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell

py -m venv .venv   
.venv\Scripts\Activate #activate virtual environment
py -m pip install -r requirements.txt

```