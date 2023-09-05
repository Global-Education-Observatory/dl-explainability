**Git & GitHub for Dummies**

---

**1. What is Git?**
- **Git** is a version control system. It lets multiple people work on a project without stepping on each other's toes, and tracks changes made over time, allowing for easy rollbacks and comparisons.

**2. What is GitHub?**
- **GitHub** is a hosting platform for Git repositories. It provides a web-based interface and collaboration features for working with Git repositories.

---

**Getting Started**

1. **Install Git**:
   - [Download Git](https://git-scm.com/downloads) for your OS and install it.

2. **Setup**:
   - Open your terminal or command prompt.
   - Set your name: `git config --global user.name "Your Name"`
   - Set your email: `git config --global user.email "youremail@example.com"`

---

**Common Git Commands**

1. **git init**:
   - Initializes a new Git repository in the current directory.
   - Usage: `git init`

2. **git clone [URL]**:
   - Clone (or download) a repository from an existing URL.
   - Usage: `git clone https://github.com/username/reponame.git`

3. **git status**:
   - Check the status of changes in the repository.
   - Usage: `git status`

4. **git add [file/directory]**:
   - Adds changes to the staging area. It tells Git you want to include updates to these files in the next commit.
   - To add all changes: `git add .`

5. **git commit -m "Commit message"**:
   - Saves the staged changes along with a short description (commit message).
   - Usage: `git commit -m "Fixed the header bug"`

6. **git push**:
   - Pushes commits made on your local branch to a remote repository.
   - Usage: `git push`

7. **git pull**:
   - Fetches changes from a remote repository and merges them into your current branch.
   - Usage: `git pull`

8. **git branch**:
   - Lists all branches in the repository.
   - Usage: `git branch`

9. **git checkout [branch-name]**:
   - Switch to another branch in the repository.
   - Usage: `git checkout feature-new-header`

10. **git merge [branch-name]**:
   - Merges the specified branch's history into the current branch.
   - Usage: `git merge feature-new-header`

---

**Basics of GitHub Workflow**

1. **Forking**: Create a copy of a repository to your own account.

2. **Cloning**: Once forked, clone the repository to your local machine.

3. **Branching**: It's a best practice to create a new branch for each new feature or fix. This ensures that the `main` branch only contains code that is stable and tested.

4. **Committing**: As you make changes, commit them to your branch.

5. **Pushing**: Push your changes up to your fork on GitHub.

6. **Pull Request (PR)**: Once you believe your changes are ready to be merged into the main codebase, open a pull request. This lets project maintainers review and discuss your changes before they are integrated.

---

**Tips**

- Always pull the latest changes from the `main` or `master` branch before creating a new feature branch.
- Write meaningful commit messages to document your changes and make it easier for others to follow along.
- Before pushing your changes, make sure to test thoroughly.
