# Set Up
## Build Environment
    ```python -m venv env```
## Install virtual Environment
    ```pip install -r requirements.txt```
## activate venv : 
### window
    ```.\env\Scripts\Activate```
### linux
    ```source env/bin/activate```
## deactivate venv: 
    ```deactivate```
## Fix can't activate env:
    ```
    run PowerShell as Admin
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
    ```