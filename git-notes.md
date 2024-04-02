# Git Workflow Cheat Sheet

1. **`git init`**
   - **Significance:** Initializes a new Git repository. This command creates a new `.git` directory in your project, which Git uses to track changes.

2. **`git clone [URL]`**
   - **Significance:** Creates a copy of an existing Git repository from a remote source. This is useful for contributing to open-source projects or collaborating on team projects.

3. **`git add [file]` or `git add .`**
   - **Significance:** Stages changes for commit. `git add [file]` adds a specific file, while `git add .` stages all changes in the directory.

4. **`git status`**
   - **Significance:** Displays the status of files in the working directory and staging area. It shows which changes are staged, not staged, and untracked.

5. **`git commit -m "[commit message]"`**
   - **Significance:** Saves your staged changes to the repository with a descriptive message. This message is important for understanding the purpose of the changes.

6. **`git push [alias] [branch]`**
   - **Significance:** Uploads all local branch commits to the remote repository. This command is how you share your commits with others.

7. **`git pull [alias] [branch]`**
   - **Significance:** Fetches and merges changes from the remote repository to your working directory. This is important for keeping your local repository up-to-date with the team's changes.

8. **`git branch`**
   - **Significance:** Lists all local branches in your repository. With options, you can also create or delete branches.

9. **`git checkout [branch-name]`**
   - **Significance:** Switches to another branch in your repository and updates the working directory. It's the way to move between different development paths.

10. **`git merge [branch]`**
    - **Significance:** Combines the specified branch’s history into the current branch. This is usually done to bring a feature into the main branch.

11. **`git fetch`**
    - **Significance:** Downloads content from a remote repository but doesn't integrate any of this new data into your working files. It's part of the process to see what others have done.

12. **`git diff`**
    - **Significance:** Shows the differences between files in the working directory and the index or between commits. This is useful for code reviews and understanding changes.
