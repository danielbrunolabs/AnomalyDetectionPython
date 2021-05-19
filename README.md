# Readme
## Overview

This repo contains notebooks and datasets used by the Analytics discipline to demonstrate how to implement anomaly detection.
## Environment Set up

You can run the noteboos in your own local environment by following the steps below.

### Install Python

You can download the latest version of Python from:
https://www.python.org/downloads/

### Install VS Code

You can download VS Code from:
https://code.visualstudio.com/download

### Install Python Extension for VS Code

1. Open VS Code **Extensions** toolbar
2. Find and install **Python Extension for VS Code from Microsoft**

    ![](images/vs_code_python_extension.png)

### Create your local virtual environment

1. Open the VS Code terminal
1. Install python package **venv** which enables the creation of local environments

   ```python
   pip install venv
   ```

1. Create the local environment in your VS Code subfolder

   ```python
   python -m venv .venv
   ```

### Activate local virtual environment in Jupyter notebook
1. Open jupyter notebook
1. Connect jupyter notbook to local virtual environment
   ![](images/activate_venv_jupyter.png)

### Activate local virtual environment in VS Code

1. In Visual Studio code launch the Command Pallette: Ctrl + Shift + P

    ![](images/activate_venv_vs_code1.png)

1. Select **Python: Select Interpreter**
1. Select your local environment

    ![](images/activate_venv_vs_code1b.png)

1. Confirm that VS Code is pointing to your local virtual environment

    At the bottom right hand corner of VS Code, you should see your local virtual envrionment.    

    ![](images/activate_venv_vs_code2.png)

### Activate virtual environement in the terminal

1. Open the terminal window inside VS Code
1. Run activate script file

    ```bash
    .venv\scripts\activate
    ```
1. Confirm you can see the environment name at the left of the command prompt
    ![](images/activate_venv_terminal.png)

### Install Python dependencies

The dependencies needed to run the notebooks are included in the **requirements.txt** file. You can install them all with the command:

```python
pip install -r requirements.txt
```
