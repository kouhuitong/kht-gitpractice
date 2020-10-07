# Course notes of STAT 992

## Part of Key Points on Version Control with Git
- Use `git config` with the `--global` option to configure a user name, email address, editor, and other preferences once per machine
- Use `git init` to initialize a repository
- Git stores all of its repository data in the `.git` directory
- `git status` shows the status of a repository
- Files can be stored in a project’s working directory (which users see), the staging area (where the next commit is being built up) and the local repository (where commits are permanently recorded)
- `git add` puts files in the staging area
- `git commit` saves the staged content as a new commit in the local repository
- Write a commit message that accurately describes your changes
- `git diff` displays differences between commits
- `git checkout` recovers old versions of files
- The `.gitignore` file tells Git what files to ignore

### Some comments
- history of repository for the course website:
  ```
  git log --abbrev-commit --graph --pretty=oneline --all --decorate
  ```
- always do git status and git diff before making a commit: that’s where we would catch that an unwanted file would get committed, or that we added a typo, or forgot something etc

### Comments from Huitong Kou
Awesome!
- `git add .` is very useful.
- `git pull` often.


