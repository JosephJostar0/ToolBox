# git

## git submodule

1. **Add a submodule:**
   - Use the `git submodule add` command to add a submodule to the parent project. For example:
     ```bash
     git submodule add [repository URL] [local path]
     ```
     Where `[repository URL]` is the Git repository URL of the submodule, and `[local path]` is the local path for the submodule within the parent project.

2. **Initialize and update submodules:**
   - In the parent project, use the following command to initialize submodules:
     ```bash
     git submodule update --init --recursive
     ```
     This initializes the submodules and fetches their content.

3. **Fetch updates for submodules:**
   - In the parent project, use the following command to fetch the latest updates for submodules:
     ```bash
     git submodule update --remote
     ```
     This fetches the latest content for submodules.

4. **Commit changes in the parent project and submodules:**
   - After making changes in the parent project that involve submodules, navigate to the submodule directory, add files, commit changes, and push to the submodule repository:
     ```bash
     cd [submodule directory]
     git add [file]
     git commit -m "commit message"
     git push
     ```
     Then, return to the parent project directory and commit changes there.

5. **Clone a repository with submodules:**
   - When cloning a repository that contains submodules, others need to initialize and update the submodules after cloning using the following command:
     ```bash
     git submodule update --init --recursive
     ```

These are the basic steps for using Git submodules. Using submodules makes it easier to manage multiple related but independently versioned projects.

## git

1. **git init**
   - Initializes a new Git repository.

2. **git clone [repository URL]**
   - Clones a remote repository to the local machine.

3. **git add [file]**
   - Adds a file to the staging area.

4. **git commit -m "commit message"**
   - Commits the staged files to the local repository with a specified message.

5. **git status**
   - Displays the status of the working directory and staging area.

6. **git log**
   - Shows the commit history.

7. **git pull**
   - Fetches changes from a remote repository and merges them into the local branch.

8. **git push**
   - Pushes local commits to a remote repository.

9. **git branch**
   - Displays the current branch.

10. **git branch [branch name]**
    - Creates a new branch.

11. **git checkout [branch name]**
    - Switches to the specified branch.

12. **git merge [branch name]**
    - Merges changes from a specified branch into the current branch.

13. **git remote -v**
    - Shows information about remote repositories.

14. **git fetch**
    - Retrieves changes from a remote repository without automatically merging.

15. **git reset [file]**
    - Unstages a file.

16. **git reset --hard [commit SHA]**
    - Resets the working directory and staging area to a specified commit.

17. **git pull origin [branch name]**
    - Fetches updates from a remote repository for a specific branch and merges them locally.

18. **git push origin --delete [branch name]**
    - Deletes a specified branch from a remote repository.
