# ds-customer-churn
This Repo contains code for customer churn prediction project
1. Install Anaconda (Python Environment) and vscode
https://www.anaconda.com/download
https://code.visualstudio.com/download


Create a Conda environment:

conda create --name myenv python=3.9
conda activate myenv
configure vscode to conda env : Open Command Palette (Ctrl+Shift+P) and search for Preferences: Open Settings (JSON). Add this to the file:

"python.condaPath": "C:/ProgramData/Anaconda3/Scripts/conda.exe"

2. Project Setup:

Clone the repository.
Install the required dependencies:
pip install -r requirements.txt


3. Steps to setup the conda environment 

conda create --name myenv python=3.9
conda init and restart vscode
conda activate myenv
pip install -r requirements.txt



4. For jupyter notebook, follow  these:
pip install jupyter
conda install ipykernel
python -m ipykernel install --user --name myenv --display-name "Python (myenv)"

Run Jupyter Noyebook from terminal by running the following command:
jupyter notebook

Install the following extensions in vscode:
Jupyter from Microsoft

5. Issue with Conda :  Conda is not recognized as an internal or external command,

Open System Properties > Environment Variables.
 
Under "System Variables," find the Path variable, and add the following if they're not already there:
 
C:\Users\YourUsername\Anaconda3
C:\Users\YourUsername\Anaconda3\Scripts
C:\Users\YourUsername\Anaconda3\condabin


check to run conda from cmd if its running :
 
Set the Default Shell in VS Code
In VS Code, open the command palette (Ctrl+Shift+P) and search for Terminal: Select Default Profile.
Choose Command Prompt or PowerShell, 
Open a new terminal (you may need to restart VS Code again).

