# Updating the Docs

1. Set-up a virtual environment and install the required packages:
    - Create a venv: ```python -m venv venv```
    - Activate the venv: ```venv/scripts/activate```
    - Install the requirements: ```pip install -r requirements.txt```
2. Make the required changes.
    - The files that reflect on the webpage can be found in the "docs" directory. You can alter ```docs/index.md``` to change the "Home" tab. You can alter ```docs/existing_training.md``` to change the "Traning Resources" tab. 
3. Before deploying, you can check how the changes look by running:
    ```mkdocs serve```
    - This will start a local server where you can preview the updated documentation.

## Rebuild and Deploy

1. To generate the updated site, run: ```mkdocs build```
    - This will rebuild the site inside the site/ directory.
2. Update the deployment by running: ```mkdocs gh-deploy```
    - This might take a few minutes.



