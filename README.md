# Useful GitHub Workflow Actions

This repository contains the GitHub Workflow Actions that I use across my projects.  

They help to automatically build and deploy code to the `gh-pages` of the GitHub repo.  
_(Under the assumption that you don't have any other build tool or webhook that will do it for you)_

## Instructions

In your target git repository, create the `.github/workflows` directory, and copy one of the `*.yml` files  
Then go to your GitHub repository settings, select Secrets, and add a new secret called `PERSONAL_TOKEN`.

You can get a token from [this page](https://github.com/settings/tokens).  
Give access to the entire `repo` scope

Make sure to commit the `.github/workflows` directory and its files.  

Then, every time you push the repository to GitHub, the workflow action will execute.


