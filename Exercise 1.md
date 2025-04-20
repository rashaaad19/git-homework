## Homework Exercises: Version Control (Git & GitHub)

### Section 1: Terminology & Concepts

**1. Match the Term:** Match the following Git terms with their correct definitions.

- Repository
- Commit
- Branch
- Merge
- Staging Area
- Conflict

**Definitions:**
- A snapshot of changes recorded in the Git history.
- A copy of your codebase for parallel development.
- A project folder tracked by Git.
- A holding area for files before committing.
- Happens when two commits modify the same line.
- Combines changes from different branches.

---

### Section 2: Command Line Practice

**2. Git Commands Quiz:** Fill in the missing commands.

1. Initialize a new Git project: `git init`
2. Create a new branch called "feature-x": `git branch feature-x`
3. Stage all files: `git .`
4. See changes that are staged: `git diff --staged`
5. Combine changes from feature-x to main: `git commit -m feature-x`

---

### Section 3: GitHub Workflow

**3. Pull Request Scenario:**

You're working on a team project. You've added a new feature in a branch called `feature/login`. What are the steps to push it to GitHub and open a pull request?

List the steps one by one.

- git checkout feature/login
- git add .
- git commit -m `feat: Added login feature`
- git push origin feature/login
- open pull request in GitHub
  - Go to your repository on GitHub
  - Click on Pull Requests button
  - Set the default branch `main`, and the compare branch `feature/login`
  - Add title and description
  - Click Create Pull Request 

---

### Section 4: Best Practices

**4. Commit Messages Challenge:**

Write a clear and meaningful commit message for the following scenario:

"You added a responsive navbar component to your web application."


--> git add -m " feat: navbar
- added new responsive navbar component"

Bad Example: `update`  
Your Turn:
feat: Added responsive navbar component
---

**Submission:**
Please submit your answers as a `.md` or `.pdf` before [21/04/2025].

