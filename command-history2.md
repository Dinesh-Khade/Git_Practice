# Command History with Descriptions

```bash
clear               # Clears the terminal screen
ls                  # Lists files and directories in the current directory
git                 # Displays Git command-line tool help
pwd                 # Prints the current working directory
git status          # Shows the current status of the Git repository
mkdir git-for-devops  # Creates a new directory named "git-for-devops"
cd git-for-devops   # Changes directory to "git-for-devops"
touch hello.txt     # Creates an empty file named "hello.txt"
vim hello.txt       # Opens "hello.txt" in Vim editor for editing
ls -l               # Lists files with detailed information (permissions, size, etc.)
rm -r hello.txt     # Deletes the file "hello.txt" recursively
git init            # Initializes a new Git repository in the current directory
touch nibba.txt nibbi.txt # Creates two empty files, "nibba.txt" and "nibbi.txt"
rm -r nibbi.txt     # Deletes the file "nibbi.txt"
git restore nibbi.txt  # Restores "nibbi.txt" to the working directory (if staged/deleted)
git add .           # Adds all changes (new, modified, deleted files) to the staging area
git commit -m "to pgls"  # Commits staged changes with the message "to pgls"
rm -r nibbi.txt     # Deletes the file "nibbi.txt" again
git config --global user.name "Dinesh"  # Sets the Git username globally to "Dinesh"
git branch          # Lists branches in the repository, indicating the current branch
echo "this is for an example" >> nibba.txt  # Appends text to "nibba.txt"
cat nibba.txt       # Displays the contents of "nibba.txt"
git commit -m "add nibba pgl pn"  # Commits staged changes with message "add nibba pgl pn"
git log             # Shows the commit history with details for each commit
git checkout -b dev # Creates a new branch "dev" and switches to it
touch nibbu.txt     # Creates an empty file named "nibbu.txt"
git checkout main   # Switches to the "main" branch
git checkout dev    # Switches back to the "dev" branch
git commit -m "add nibbu"  # Commits staged changes with message "add nibbu"
git log --oneline   # Shows the commit history in a simplified one-line format
history             # Lists all previously run commands in the session
