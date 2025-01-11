# Git Commands

## File and Directory Operations
- **List files in the current directory**: `ls`
- **Create a new directory**: `mkdir git-for-devops`
- **Navigate to a directory**: `cd git-for-devops/`
- **List files with detailed information**: `ll`

## Initializing a Git Repository
- **Initialize a new Git repository**: `git init`

## Creating and Managing Files
- **Create files**: `touch nibba.txt nibbi.txt`
- **Open a file in the editor**: `vi nibba.txt`, `vi nibbi.txt`

## Checking Status
- **Check the status of the repository**: `git status`
- **Incorrect command example**: `gut status` (Typo corrected to `git status`)

## Staging Files
- **Stage a specific file**: `git add nibba.txt`
- **Stage another file**: `git add nibbi.txt`

## Committing Changes
- **Commit with a message**: `git commit -m "thank you for adding me"`

## Configuring Git
- **Set global email**: `git config --global user.email "rajprit933@gmail.com"`
- **Set global username**: `git config --global user.name "pritam"`

## Removing Files
- **Remove a file**: `rm nibba.txt`

## Restoring Files
- **Restore a file**: `git restore nibba.txt`

## Viewing File Content
- **View file content**: `cat nibba.txt`, `cat nibbi.txt`

## Creating Branches
- **List branches**: `git branch`
- **Create and switch to a new branch**: `git checkout -b dev`
- **Switch back to the master branch**: `git checkout master`
- **Switch between branches**: `git checkout dev`

## Managing Changes on Branches
- **Create and add a new file**: `touch nibbu.txt`, `git add nibbu.txt`
- **Commit changes**: `git commit -m "added nibbu"`

## Viewing History
- **View commit log**: `git log`
- **View condensed commit log**: `git log --oneline`

## Exploring Git Internals
- **Navigate to the `.git` folder**: `cd .git/`
- **Explore Git logs and references**: 
  - `cd logs/`, `cd refs/`, `cd heads/`
  - `cat master`

## Additional Commands
- **Clear terminal output**: `clear`
- **Print current directory**: `pwd`
- **View history of all commands**: `history`
