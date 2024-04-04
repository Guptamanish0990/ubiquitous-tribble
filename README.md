# MLGUI


> ## Technology
- Python
- Django 3.2
- MySQL
- HTML
- CSS
- Bootstrap
- Machine Learning
- React.js
- D3.js

> ## Cloud
- GCP

> ## Ops Pipeline
- Mlflow and DVC

> ## Deployment
- cloud

> ## Installation
- get ready with Anaconda3.
- create a conda environment.
    ```git
    conda create -n env_name python=version -y
    ```

- install all dependencies.
    ```git
    pip install -r requirements.txt
    ```
- start the application.
    ```bash
    cd ram
    python manage.py run server
    ```
- to stop the server press ctrl+c.

> ## Contribution
To Contribute to this project follow the below command.
- fork the current repository.
- after forking this repository, another will be created one more repository in your GitHub account with `username/MLGUI-backend`. and click on the `username/MLGUI-backend` repository.
- go to the code button, and copy the repository URL.
- create an isolated `folder` for this project on your `local computer`.
- open a particular folder with `vs code` or any other editor.
- open the terminal at the created new folder location, and run the below command.
    ```git
  
    ```
- after cloning this repository, let's check whether the repository is up to date or not.
    ```git
    git remote -v
    # There will be two names 1 is upstream and 2 is origin. if upstream is not visible then create upstream with the below command.

    git pull upstream 
    ```
- create a new branch for editing code.
    ```git
    git checkout -b branch_name
    ```
    above command creates a new branch and sets it for running the current branch state. after this, any editing in code will be saved in the newly created branch. to check the running branch run the below command output will be a list of the branch, the running branch is represented with `*branch_name`.
    ```git
    git branch
    ```
- after editing the code part, you need to save your changes and pull those changes to the master repository with the below command.
    ```git
    git add. 
    # We can use "git add -A" or "git add --a"
    git commit -m "message what you have made changes in the repository"
    git push -u origin branch_name
    #we can use "git push origin branch_name" without the -u flag.
    ```


> ## Contributor
:) Manish Gupta 


# * Thank You! *
