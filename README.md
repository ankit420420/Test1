# Test1
This is Test1 repository

# ------------------------------------------USING GITHUB MANUALLY************************************************************  

# To upload projects in GITHUB
    a.	Create GITHUB repository
    b.	Create README.md file in local project
    c.	Create .gitignore file in local project and add the files to ignore uploading to GITHUB
    d.	Uploading project to GITHUB


# Create GIT repository in GITHUB
    Step 1: Click on NEW in Github homepage
    Step2: It opens up a page to enter git repository details. 
        •	Enter the repository name
        •	Add repository description
        •	Select repository as Public or Private. For now set it as public (Public repository can be seen by anyone. Private 
            repository will be accessible when permission is granted)
        •	Select checkbox for “Add readme file”
        •	Select Node for “Add .gotignore”
        •	Select none for “License”
    Step3: Click on Create Repository

    It creates a repository with initial commit with
        •	Branch name as main
        •	README.md
        •	.gitignore files and

# Notes
    .gitignore file contains
        a)	dist
        b)	node_modules
        c)	*.log
        d)	.env


# Create README.md file in project
    Create a README.md fle in project root directory to add notes related to project, useful at later stages of projects and others working on the project

# Create .gitignore file in project and add the files to ignore uploading to GITHUB
    Create a .gitignore file in project root directory and add the data of .gitignore file created when repository is created


# Uploading project to GITHUB
    To upload project to github follow the following steps:
        •	git init
        •	git add –A
        •	git commit –m <”commit message”>
        •	git branch –m main     
                      by default local branch is create with name as “master”. To change name use the above command
        •	git remote add origin <github repository url>
        •	git push -u -f origin main                      (//main or whatever is your branch name)
                         (-u: This switch makes the remote GitHub repo the default for your existing project.                     
                         -f: This switch forces Git to overwrite any files that already exist on GitHub with your existing 
                            project’s files.)


    This pushes the current project on github

-----------------------------------------------------------------------------------------------------------------------------

# To update a project on GITHUB
    After making changes in project follow these steps:
        •	git add –A
        •	git commit –m <”commit message”>
        •	git pull
    
    If updated code is pushed from repository then follow steps 1,2,3 agin is same   
   Order, else move to next step
        
        •	git push

-----------------------------------------------------------------------------------------------------------------------------

# To clone a project from GITHUB
    •	Open the project on GTIHUB
    •	Click on Code button
    •	Copy the git url
    •	Open the terminal in the project’s root directory, then follow the following commands
    •	npm i              (as node_modules folder is not uploaded on github so it installs that folder in project)

-----------------------------------------------------------------------------------------------------------------------------
