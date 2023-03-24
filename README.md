# PAPER BOORE

This repo contains the task of Boore's paper. 

# Working with git

## Create and clone a repo

- Create a repo on the github website inside jorvend user

- git clone https://github.com/jorvend/JV-Research.git (on the green button "code")

## Pull changes from github repo

- git pull

## Make changes from the github repo

- git status (to see what is changed)

- write in the gitignore file the files I don't want to push

- git add . (to add everything)

- git status (to see again if the changes are added)

- git commit -m "Update gitignore"

- git push (to push it to the github cloud)

# Working with this repo

## 1. Python virtual environment setup

Create a virtual environment with python version 3.9 (the maximum supported by OpenSeesPy latest version 3.4.0.2). From the working directory execute:

`py -3.9 -m venv JV-Research_env` (ONLY FIRST TIME)

Each time, previous to start working, execute:

`./JV-Research_env/Scripts/activate` (ALWAYS)

You'll see something like (in Windows):

`(JV-Research_env) PS C:\_\UCI\UCI_paper_Boore> ` (ALWAYS)

## 2. Install OpenSeesPy and other dependencies

You can install all the dependencies from the requirements.txt file

`(JV-Research_env) PS C:\_\UCI\UCI_paper_Boore> python -m pip install -r requirements.txt` (EACH TIME I ADD NEW LIBRARIES)

## 3. Start a Jupyter Notebook

### Option: From installed jupyter kernel

- From the activated python env install (ONLY FIRST TIME)

  `(JV-Research_env) PS C:\_\UCI\UCI_paper_Boore> python -m pip install notebook`

  `ipython kernel install --user --name=JV-Research_env`

- Run:

  `jupyter notebook`

- Connect to a Jupyter Kernel with your venv.