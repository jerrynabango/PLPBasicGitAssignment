**Git Basics: A Simple Guide**

**What is Git:**
Git is a version control system that helps you manage changes to your code and collaborate with others efficiently. It's like a time machine for your code, allowing you to track changes, revert to previous versions, and work on different features simultaneously.

**Key Concepts:**
- **Repository**: A repository, or repo, is like a folder that contains all your project files and their history.
- **Commit**: A commit is a snapshot of your code at a specific point in time. It records changes you've made and allows you to track your progress.
- **Branch**: A branch is like a parallel universe where you can work on new features or fixes without affecting the main codebase. You can create, switch between, and merge branches as needed.
- **Merge**: Merging combines changes from different branches into one. It's like combining puzzle pieces to create a complete picture.

**Common Git Commands:**
1. `git init`: Initializes a new Git repository in the current directory.
2. `git clone <repository_url>`: Copies an existing repository from a remote server to your local machine.
3. `git add <file_name>`: Adds changes in a file to the staging area, preparing them for the next commit.
4. `git commit -m "Commit message"`: Commits staged changes to the repository with a descriptive message.
5. `git status`: Shows the current status of your working directory and staging area.
6. `git branch`: Lists all branches in the repository. Use `-a` to show remote branches.
7. `git checkout <branch_name>`: Switches to the specified branch.
8. `git merge <branch_name>`: Merges changes from the specified branch into the current branch.
9. `git pull`: Fetches changes from a remote repository and merges them into the current branch.
10. `git push`: Pushes local commits to a remote repository.

**Example Usage:**
1. Initialize a new repository:
   ```bash
   git init
   ```
2. Add files to the staging area:
   ```bash
   git add .
   ```
3. Commit changes:
   ```bash
   git commit -m "Initial commit"
   ```
4. Create a new branch:
   ```bash
   git branch feature-branch
   ```
5. Switch to the new branch:
   ```bash
   git checkout feature-branch
   ```
6. Make changes and commit them:
   ```bash
   git add .
   git commit -m "Add new feature"
   ```
7. Merge changes into the main branch:
   ```bash
   git checkout main
   git merge feature-branch
   ```
8. Push changes to a remote repository:
   ```bash
   git push origin main
   ```
