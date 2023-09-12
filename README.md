# Ctrl+Future Training: Github Fundamentals  
## Training to introduce the cohorts on how to push from a local envoriment to Github.  
## Common Linux Commands  
- Create a directory: **mkdir** name of the directory. This command will create a directory.
- Change directory: **cd** name of the directory. This command helps you to move from one directory to another.
- To create a file: **touch** name of the file. This command helps you to create a file within the directory.
- To list the contents of the file: **ls**
- To remove a file: **rm** file name. This command removes a file.
- To remove an empty directory: **rmdir** name of the directory. This command removes an empty directory.
## Download Gitbash  
- https://git-scm.com/downloads
## Configure Gitbash  
- **git config --global user.name "Your name"**
- **git config --global user.email "Your e-mail"**
## Prepare your working envoriment  
- **mkdir website**
- **cd website**
- **git init**
- **touch index.html**
- **vim index.html** (to add content to the html file)
## Clone you repository  
- **git remote add origin (url from the repo you created)** - Use HTTPS link
## Push from your local envoriment to Github  
- **git status** - This helps to check the files on the staging area.  
- **git add index.html** - This adds your files to the staging area.
- **git commit -m "Commit message"** - Commit command helps you to take a snapshot of what you do at that moment of time.
- **git push origin master** - This command pushes the changes to the repository. 
