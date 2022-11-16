# Simple CLI Command

Below is a list of CLI commands that we'll use occasionally.

## Working with files and folders

```bash

# creating a folder
mkdir <folder-name>

# creating a file
touch <file-name>

# navigating through folders
cd <folder-name>

#going one step behind a folder
cd ..

#navigating back to the root folder
cd ~

#removing files and folders that have no permissions
rm <folder/file name>

#removing files and folders that have permissions
rm -rf <folder/file name>

#opening a folderin vs code
code <folder/file name/current directory>

#list all files within a folder (unhidden)
ls

#list all the files within a folder (with hidden)
ls -a
```

## Basic git Commands

```bash

#Initialize an empty git repository
git innit 

#To link local repository to 
git remote add origin <ssh key>

#Checking the status of your repository
git status

#Adding files/folders to the pipeline
git add <file name/path>

#Committing your added files 
git commit -m <"message">

#Pushing your committed files to the remote git repository
git push origin main

#Cloning a project from remote depository to local repository (using SSH key)
git clone <ssh key>


```