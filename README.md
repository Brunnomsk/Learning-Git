## Assignment: Git Workflow Basics

This assignment demonstrates the basics of Git workflow through hands-on practice. Below are the steps I took to complete the assignment and explanations for each command used:

1. **Create a Folder**:  
   `mkdir learn_git`  
   Created a new directory called `learn_git` for this project.

2. **Change Directory**:  
   `cd learn_git`  
   Moved into the newly created `learn_git` directory.

3. **Create a File**:  
   `touch third.txt`  
   Created an empty file named `third.txt`.

4. **Initialize Git Repository**:  
   `git init`  
   Initialized an empty Git repository in the current folder.

5. **Add File to Staging Area**:  
   `git add third.txt`  
   Staged the `third.txt` file, making it ready for the next commit.

6. **Commit Changes**:  
   `git commit -m "adding third.txt"`  
   Committed the staged changes with the message "adding third.txt".

7. **Check Commit History**:  
   `git log`  
   Viewed the commit history to verify the recent commit.

8. **Create Another File**:  
   `touch fourth.txt`  
   Created a new file called `fourth.txt`.

9. **Stage and Commit the New File**:  
   `git add fourth.txt`  
   Staged the new `fourth.txt` file.  
   `git commit -m "adding fourth.txt"`  
   Committed the file with the message "adding fourth.txt".

10. **Remove a File**:  
    `rm third.txt`  
    Deleted the `third.txt` file.

11. **Stage and Commit the Removal**:  
    `git add .`  
    Staged the deletion of the file.  
    `git commit -m "removing third.txt"`  
    Committed the change with the message "removing third.txt".

12. **Review Commit History Again**:  
    `git log`  
    Checked the commit history to verify all changes.

13. **Update Global Git Settings**:  
    `git config --global core.pager cat`  
    Changed the global Git setting to display output directly in the terminal.

14. **List All Global Git Configurations**:  
    `git config --list --global`  
    Listed all the global Git configurations on my machine.

Finally, I captured screenshots for each step and pushed them to this GitHub repository as instructed.
