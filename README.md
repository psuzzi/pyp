# pyp
Python Programming

This repo contains some examples of python programming. 

## Prerequisites

- Python 3.7+
- pip (Python package installer)

## Setup CLI

Do the following on the command line only, before opening VSCode

1. Clone the repository:
   ```
   git clone git@github.com:<your-organization>/<your-repository>.git
   cd <your-repository>
   ```

2. Create a virtual environment:
    ```
    python -m venv venv
    ```

3. Activate the virtual environment:``
   - Windows:
    ```
    .\venv\Scripts\activate
    ```
   - macOS/Linux:
    ```
    source venv/bin/activate
    ```

4. Check which python are you running:
    ```
    python -c "import sys; print(sys.executable)"
    ```

5. Install dependencies:
requirements.txt is a script that should contain the dependencies to be installed in your repository, e.g. (Add an example here)
To install the requirements to your venv, just do this:
   ```
   pip install -r requirements.txt
   ```

6. Deactivate
To terminate the session in CLI
    ```
    deactivate
    ```

## Setup VSCode
Prerequisite: you already did the venv setup via CLI, and you see the /venv folder, that usually is .gitignored. 

Check if VSCode is already using the /venv folder for your python environment: Type the following command in VSCode terminal
    ```
    python -c "import sys; print(sys.executable)"
    ```

If your VSCode interpreter is not set to use the local /venv folder, just tell VSCode to do so as follows:

1. Open the project in VSCode
2. Use the command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS)
3. Select "Python: Select Interpreter"
4. Choose the interpreter from the local `venv` folder

From now on, every time you use python in this project, you will use the interpreter pointing to your local /venv folder, including when you install requirements.


