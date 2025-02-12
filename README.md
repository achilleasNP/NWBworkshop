# NWB Tutorial directory

Workshop material for NWB workshop.

There are three ways to interactively work on the notebook.
Starting from the easiest they are:
1. Run using binder. You only need to click on the badge and when the service is up you should be ready to go:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/achilleasNP/NWBworkshop.git/HEAD?labpath=notebooks%2Fneuroconv.ipynb)

2. Using github codespaces (requires a github account).
    - Login into github
    - Select your image -> settings -> At editor preference select JupyterLab (You can change this later).
    - Fork the repository by clicking fork button.
    - Go in your forked repository.
    - Select the code dropdown (Green button) -> the Codespaces tab -> Create codespace on main.
    - Wait until the codespace is up it will take a few minutes.
    - Select the neuroconv.ipynb notebook from notebooks.
    - Change the kernel to workshop.
    - At the end of the workshop/using the notebook make sure you [*stop the codespace*](https://docs.github.com/en/codespaces/developing-in-a-codespace/stopping-and-starting-a-codespace)

3. Using a local jupyter installation
    - Create a virtual environment
    ``` python3 -m venv workshop ```
    - Activate the environment.
    ``` . workshop/bin/activate ``` 
    - Install the requirements using the requirements.txt file.
    ``` pip install -r requirements.txt ```
    - Create a jupyter kernel with the virtual environment dependencies
     ``` python -m ipykernel install --user --name=workshop ```
    - Run jupyter notebook (or jupyter lab) and select the `workshop` kernel



