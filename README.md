# Itachi-Uchiha

## Explain Version Control
Version control is a system that records changes to a file or set of files over time, allowing you to revert to previous versions, track changes, and collaborate with others. It helps developers manage their code efficiently.

---

## Explain the Difference Between Git and GitHub
- **Git**: A distributed version control system used to track changes in source code during software development. It operates locally on your computer.
- **GitHub**: A cloud-based platform that hosts Git repositories and provides collaborative tools like pull requests, issue tracking, and CI/CD integration.

---

## List 3 Other GitHub Alternatives
1. **GitLab**: Similar to GitHub, with features like CI/CD and project management tools.
2. **Bitbucket**: Focuses on integration with Atlassian tools like Jira and Trello.
3. **SourceForge**: Older platform for hosting open-source projects, now modernized.

---

## Explain the Difference Between `git fetch` and `git pull`
- **`git fetch`**: Downloads changes from the remote repository but does not merge them into your local branch.
- **`git pull`**: Downloads changes and automatically merges them into your current branch. It's essentially a combination of `git fetch` and `git merge`.

---

## Explain in Simple Terms Git Rebase and the Command for It
- **Rebase**: Re-applies your commits on top of another branch to create a linear history. It's useful for keeping a cleaner project history.
- **Command**:
    ```bash
    git rebase <branch_name>
    ```

---

## Explain in Simple Terms Git Cherry-Pick and the Command for It
- **Cherry-pick**: Selectively applies specific commits from one branch to another.
- **Command**:
    ```bash
    git cherry-pick <commit-hash>
    ```