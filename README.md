# Cheat Sheet

## Basic Linux Commands.

### mkdir

Creates new directories.

Usage:   `mkdir <dir>` <br>
Example: `mkdir ~/cmds_cs` 

---

### cd

Chages your current working directory.

Usage:   `cd <dir>` <br>
Example: `cd ~/cmds_cs`

---

### touch

Creates empty file.

Usage: `touch <dir/file>` <br>
Example: `touch README.md`

---

### nvim - editor 

Edit file with editor of choice.

Usage:   `nvim <dir/file>` <br>
Example: `nvim README.md`

---

### ssh-keygen

Generates a new ssh key. Can be used to connect to github.

Usage:   `ssh-keygen -t ed25519 -C "your@email"` <br>

---

### git init 

Creates a new local git repository.

Usage:   `git init` <br>

---

### git add 

Stages files to be commited to a branch.

Usage:   `git add <files>` <br>
Example: `git add .` 

---

### git commit 

Saves changes made to files to a branch.

Usage:   `git commit -m "message"` <br>

---

### git branch 

Creates a new branch.

Usage:   `git branch <branch_name>` <br>
Example: `git branch new-command`

---

### git checkout 

Swictches to a different branch.

Usage:   `git checkout <branch_name>` <br>
Example: `git checkout new-command`

---

### git push 

Pushes all the changes to a remote repo.

Usage:   `git push --all <remote_repo>` <br>
Example: `git push --all origin`

---

### git merge 

Merges a branch into the current branch.

Usage:   `git merge <other_branch` <br>
Example: `git merge new-command`

---

### git diff 

Shows the changes made since last commit.

Usage:   `git diff`

---

### git pull 

Fetches all the updated changes from the remote repo.

Usage:   `git pull origin`

---

### git clone 

Makes a local copy of a remote repo.

Usage:   `git clone <remote_repo_url>` <br>
Example: `git clone https://github.com/8epu3/cmds_cs.git`
