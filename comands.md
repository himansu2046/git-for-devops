# **Git Commands**

## **1. Repository Initialization**
Set up a new Git repository to start tracking changes.

- **Initializing a Repository:**  
  `git init`  
  *Creates a new Git repository in the current directory.*

## **2. File and Directory Management**
Manage files and directories in the repository.

- **Creating Files:**  
  `touch <file_name>`  
  *Creates a new file with the specified name.*

- **Removing Files from the Working Directory:**  
  `rm <file_name>`  
  *Deletes the specified file from the working directory.*

- **Removing a Directory:**  
  `rm -r <directory_name>`  
  *Recursively deletes the specified directory and its contents.*

- **Listing Files in a Directory:**  
  `ls`  
  *Displays the files and directories in the current directory.*

- **Viewing File Content:**  
  `vim <file_name>`  
  *Opens the specified file in the Vim text editor.*

## **3. Staging and Committing Changes**
Stage and commit your changes to the repository.

- **Adding Files to Staging Area:**  
  `git add <file_name>`  
  *Adds the specified file to the staging area for the next commit.*

- **Adding All Files to Staging Area:**  
  `git add .`  
  *Adds all changes in the current directory to the staging area.*

- **Removing Files from the Staging Area (Unstage):**  
  `git rm --cached <file_name>`  
  *Removes the specified file from the staging area without deleting it from the working directory.*

- **Committing Changes:**  
  `git commit -m "commit message"`  
  *Records changes in the repository with a descriptive commit message.*

## **4. Repository Status and Log**
Check the current status and history of the repository.

- **Checking the Status of the Repository:**  
  `git status`  
  *Displays the current status of the working directory and staging area.*

- **Checking Git Log:**  
  `git log`  
  *Shows the commit history for the repository.*

- **Checking Git Log (Oneline View):**  
  `git log --oneline`  
  *Displays a compact view of the commit history.*

## **5. Branch Management**
Manage branches in the repository.

- **Creating a New Branch:**  
  `git checkout -b <branch_name>`  
  *Creates a new branch and switches to it immediately.*

- **Switching Branches:**  
  `git checkout <branch_name>`  
  *Switches to the specified branch in the repository.*

- **Viewing Branches:**  
  `git branch`  
  *Lists all branches in the repository and indicates the current branch.*

## **6. Configuration**
Configure user information for the Git repository.

- **Configuring Git Username:**  
  `git config --global user.name "your_username"`  
  *Sets the username for Git commits globally.*

- **Configuring Git Email:**  
  `git config --global user.email "your_email@example.com"`  
  *Sets the email address for Git commits globally.*

## **7. Restoring Files**
Restore files to their previous state.

- **Restoring Files:**  
  `git restore <file_name>`  
  *Restores the specified file to its last committed state.*


  ##.8 Check the remote url for the git hub
    git remote -v
  pull the file from remote to local
    git pull origin <branchname>
    push the file from local to remote
    git push
