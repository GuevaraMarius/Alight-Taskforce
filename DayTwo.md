# Morning
## Git Basics?
Git is a distributed version control system used to track changes in source code during software development.

## Configuration
Set up your Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

## Basic Commands

### Create a New Repository
`git init <repository-name>`

### Clone an Existing Repository
`git clone <repository-url>`

### Check Status
`git status`

### Add Changes
`git add <file-name>`  
`git add .`           

### Commit Changes
`git commit -m "Your commit message"`

### View Commit History
`git log`

### Push Changes
`git push origin <branch-name>`

### Pull Changes
`git pull origin <branch-name>`

### Create a Branch
`git checkout -b <branch-name>`

### Switch Branches
`git checkout <branch-name>`

### Merge Branches
`git merge <branch-name>`

### Delete a Branch
`git branch -d <branch-name>`
# Add a remote repository
`git remote add <remote-name> <repository-url>`

# List remote repositories
`git remote -v`

### Modify commit
`git commit --amend`

# Push changes to remote repository
`git push <remote-name> <branch-name>`

# Pull changes from remote repository
`git pull <remote-name> <branch-name>`

# Fetch changes from remote repository
`git fetch <remote-name>`

# Remove a remote repository
`git remote remove <remote-name>`

# Change the remote URL
`git remote set-url <remote-name> <new-repository-url>`