# Let's create a text file with the neatly formatted explanation of the Git commands
output_text = """
1. git status
   Usage: Displays the current state of the working directory and staging area.
   Purpose: Helps you see which changes are staged for commit, which aren’t, and any untracked files.

2. git add <file>
   Usage: Stages changes of the specified file(s) for the next commit.
   Example: git add nibba.txt adds nibba.txt to the staging area.

3. git commit
   Usage: Saves the current state of the repository, taking a "snapshot" of the staged changes.
   Without -m: Opens a text editor to enter a commit message.

4. git commit -m "<message>"
   Usage: Commits changes with a descriptive message in one step.
   Example: git commit -m "adding nibba" creates a commit with the message "adding nibba."

5. git log
   Usage: Displays the commit history, showing details such as the author, date, and commit message for each commit.

6. git branch
   Usage: Lists all branches in the repository and highlights the current branch.

7. git checkout -b <branch_name>
   Usage: Creates a new branch and immediately switches to it.
   Example: git checkout -b dev creates and switches to a new branch called dev.

8. git rm --cached <file>
   Usage: Removes a file from the staging area but keeps it in the working directory (i.e., stops tracking the file without deleting it).
   Example: git rm --cached nibbu stops tracking the file nibbu.

9. git commit <file>
   Usage: This is incorrect usage; a commit should always have a message or be used with staged files.
   Correct Usage: git commit -m "message" to commit with a message, or just git commit to commit all staged changes.

10. git checkout <branch>
   Usage: Switches to the specified branch.
   Example: git checkout master switches to the master branch.

11. git log --oneline
   Usage: Displays the commit history in a simplified format, showing just the commit hash and message on a single line.
"""
