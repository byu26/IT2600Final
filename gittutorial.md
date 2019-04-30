# Here are instructions on managing a project with Git through the command line

--- 
#### Common Git Commands used in this tutorial
* ```git clone``` allows you to clone the repository to a directory.
* ```git init``` after cloning the repository, this allows you to initialize your local repository with git.
* ```git add . ``` this allows you to add all modified and untracked files in the directory and prepares them for the commit. You can also use ```git add -A```.
* ```git commit -m "commit comment"``` this commits your changes made with a short comment about what changes were made. 
* ```git branch branchName``` this allows you to create a new branch to edit on
* ```git push``` pushes your changes to the remote repository. ```git push -u origin branchName``` pushes changes to the specified branch name. In our case, the ```master``` branch. 
##### For more Git commands see [this](https://github.com/joshnh/Git-Commands) link. 
---
#### Instructions
* The first step is to create a GitHub Account if you haven't already 
* The second step is to make the repository.
    * You can initialize the repository with a README to help with instructions.
* Next open up Terminal by pressing ```command+space``` and typing in terminal
    * Change to the directory you want the project to be on with ```cd``` and then the name of the directory. For example: ```cd Desktop/ ``` 
* Now to clone your repository to the selected directory type ```git clone```*```https://LinkToYourGitHubRepository```*
* After cloning the repository to your remote, you will want to change into that directory. If the repository was named GitTutorial, it would be  ```cd GitTutorial```
* The repository should already have a .git. If not, you will want to initialize the repository with ```git init``` 
    * Use ```git add remote origin linkToRepository``` to add the remote ```origin``` if it does not already exist. If it does exist you will get the message ```fatal: remote origin already exists.```
* Now that everything is set up you can start editing the README.md and also create other files in the repository.
    * To do this, you can open the file on a text editor like Brackets and any changes you make and save can be updated on the remote and the repository using Git. 
    * You can also create new files in the repository as you would normally with File>New> as long as you save it inside the same folder/directory you are working in. 
#### Making Changes & Committing 
* As you edit the files, be sure to save and commit often so it can be tracked and easily reverted if any big mistakes were made. 
    * To commit changes, you first need to prepare the changes to be committed using ```git add . ``` or ```git add -A```
    * Next, you'll want to commit the changes using ```git commit -m "commit description"```. 
    * Finally, you can push the commit to the master branch or whichever branch you made to edit on. To do this, type ```git push -u origin master```. 

