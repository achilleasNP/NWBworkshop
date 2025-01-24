# NWB Tutorial directory

Workshop material for NWB workshop.

There are three ways to interactively work on the notebook.
Starting from the easiest they are:
1. Run using binder. You only need to click on the badge and when the service is up you should be ready to go:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/achilleasNP/NWBworkshop.git/HEAD?labpath=notebooks%2Fneuroconv.ipynb)
2. Using github codespaces (requires a github account).
  - Login into github
  - Fork the repository by clicking fork button.
  - Go in your forked repository.
  - Select the code dropdown (Green button) -> the Codespaces tab -> Create codespace on main.
  - Wait until the codespace is up it will take a few minutes.
  - You can now close your codespace.
  - Go to your codespaces -> Click on the `...` next to the codespace you created -> Select open in JupyterLab
  - *Make sure you close your codespace after you are done* (otherwise you will run out of credits)

3. Using a local jupyter installation
  - Create a virtual environment
  - Install the requirements using the requirements.txt file.
    ``` 
    pip install -r requirements.txt 
    ```
  - Create a jupyter kernel with the virtual environment dependencies
     ``` 
     python -m ipykernel install --user --name=nwb_workshop 
     ```
  - Run jupyter notebook (or jupyter lab) and select the `nwb_workshop` kernel



