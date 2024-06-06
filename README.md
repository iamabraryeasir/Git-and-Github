# Git and Github ⚡

## 👉 Git Setup In Local.

1. Goto this link [Git Download](https://git-scm.com/downloads) and download and install git according to your system preference.
2. Goto this link [Github.com](https://github.com/) and Create a account on Github.

## 👉 Important Theory Questions.

### 1️⃣ What is Git??

Git is a popular, open source, free, fast & scalable `version control system` software.

### 2️⃣ What is a Version Control System??

A version control system is a tool/software that helps us in tracking changes in our code/source code.

### 3️⃣ What is Github??

Github is a service/website that helps developer to manage there code on the cloud using Git.

### 4️⃣ Git is primarily used for 2 things.

1. Track the code history.
2. Collaborate with Multiple Developers.

### 5️⃣ What is a Repo??

Usually when we track projects using Git or upload them on Github we treat them as folders. And in the language of Git this folders are called Repositories or in short Repos. So repo is a folder in the language of Git.

### 6️⃣ There are 2 steps to add changes in Github.

1. Add the change.
2. Commit the change.

### 7️⃣ What does commit means??

The commit means taking a snapshot of a code version and add the code to the main code base. Basically creating a history for a specific code version.

### 8️⃣ Generally we have 4 type of states in git.

1. Untracked => New file that git doesn't yet track.
2. Modified => Changed.
3. Staged => File is ready to be committed.
4. Unmodified => Unchanged.

### 9️⃣ What is a Pull Request???

It lets you tell others about changes you've pushed to a branch in a repository on GitHub.

### 1️⃣0️⃣ What does Pull Command do??

It is used to fetch and download content from a remote repo and immediately update the local repo to match that content.

### 1️⃣1️⃣ What is Merge Conflicts??

It is an event that takes place when Git is unable to automatically resolve differences in code between two commits.

## 👉 All Git Commands and there meanings.

### 1️⃣ Checking Git Version.

```bash
git --version
```

### 2️⃣ Configure Git Username.

```bash
git config --global user.name "yourUserName"
```

### 3️⃣ Configure Git Email.

```bash
git config --global user.email "youremail@gmail.com"
```

### 4️⃣ To Check if the Username and Email is properly configured.

```bash
git config --list
```

### 5️⃣ To clone a github repo to local system.

```bash
git clone <--repoLink-->
```

### 6️⃣ To display the status of the codebase.

```bash
git status
```

### 7️⃣ To View all the files including hidden file (Linux/Bash).

```bash
ls -a
```

### 8️⃣ To View all the files including hidden file (Windows/PowerShell).

```bash
dir -force
```

### 9️⃣ To add specific changed file.

```bash
git add <--fileName-->
```

### 1️⃣0️⃣ To add all the changed Files.

```bash
git add .
```

### 1️⃣1️⃣ To commit the Changes to the repo.

```bash
git commit -m "Commit Massage"
```

### 1️⃣2️⃣ To push/upload the local changes to Github/Cloud.

```bash
git push -u origin main
```

### 1️⃣3️⃣ Initialize git in a directory.

```bash
git init
```

### 1️⃣4️⃣ To push/upload the local changes to Github/Cloud.

```bash
git push -u origin main
```

### 1️⃣5️⃣ Adding the remote/github origin.

```bash
git remote add origin <--repoLink-->
```

### 1️⃣6️⃣ To verify the remote origin.

```bash
git remote -v
```

### 1️⃣7️⃣ To check the branch.

```bash
git branch
```

### 1️⃣8️⃣ To rename a branch to main.

```bash
git branch -M main
```

### 1️⃣9️⃣ Creating new branch.

```bash
git checkout -b <--new branch name-->
```

### 2️⃣0️⃣ Navigating through branches.

```bash
git checkout <--branch name-->
```

### 2️⃣1️⃣ Deleting a branch.

```bash
git branch -d <--branch name-->
```

### 2️⃣1️⃣ Comparing 2 branches.

```bash
git diff <--branch name-->
```

### 2️⃣2️⃣ Pulling remote content from Github.

```bash
git pull origin main
```

### 2️⃣3️⃣ Merging branches.

```bash
git merge <--other branch name-->
```

### 2️⃣4️⃣ See commit history.

```bash
git log
```

### 2️⃣5️⃣ Git reset with change in code editor.

```bash
git reset --hard <--Commit Hash-->
```
