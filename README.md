# Git Cheatsheet

A compact and beginner-friendly Git cheatsheet containing 50 essential commands. From initialization to branching, stashing, and even submodules — this guide provides quick access to frequently used Git operations with clear usage and purpose.

| #  | Category     | Command                                          | Purpose                                                                 |
|----|--------------|--------------------------------------------------|-------------------------------------------------------------------------|
| 1  | Config       | `git config --global user.name "name"`          | Set global Git username                                                 |
| 2  |              | `git config --global user.email "email"`        | Set global Git email                                                    |
| 3  |              | `git config --global color.ui auto`             | Enable colorized Git output                                             |
| 4  | Init         | `git init`                                       | Initialize a new Git repository                                         |
| 5  | Clone        | `git clone <url>`                                | Clone a remote repository                                               |
| 6  | Status       | `git status`                                     | Display the state of the working directory and staging area             |
| 7  | Add          | `git add <file>`                                 | Add a file to the staging area                                          |
| 8  |              | `git add .`                                      | Add all changes in the current directory to the staging area            |
| 9  | Commit       | `git commit -m "message"`                        | Commit staged changes with a message                                   |
| 10 |              | `git commit --amend`                             | Amend the previous commit                                               |
| 11 | Branch       | `git branch`                                     | List all local branches                                                 |
| 12 |              | `git branch -a`                                  | List all branches, including remote                                     |
| 13 |              | `git branch <name>`                              | Create a new branch                                                     |
| 14 |              | `git branch -d <branch>`                         | Delete a local branch                                                   |
| 15 | Checkout     | `git checkout <branch>`                          | Switch to an existing branch                                            |
| 16 |              | `git checkout -b <branch>`                       | Create and switch to a new branch                                       |
| 17 | Merge        | `git merge <branch>`                             | Merge a branch into the current branch                                  |
| 18 | Rebase       | `git rebase <branch>`                            | Reapply commits on top of another base tip                              |
| 19 | Reset        | `git reset --hard <commit>`                      | Reset current HEAD to the specified state                               |
| 20 |              | `git reset --hard HEAD~2`                        | Roll back the current branch by two commits                             |
| 21 |              | `git reset --soft <commit>`                      | Reset HEAD to the specified commit, keeping changes staged              |
| 22 | Revert       | `git revert <commit>`                            | Revert a commit by creating a new commit                                |
| 23 | Log          | `git log`                                        | Show commit logs                                                        |
| 24 |              | `git log --oneline`                              | Show condensed commit logs                                              |
| 25 | Diff         | `git diff`                                       | Show changes between commits, commit and working tree, etc              |
| 26 |              | `git diff --staged`                              | Show changes between staged changes and last commit                     |
| 27 | Stash        | `git stash`                                      | Stash the changes in a dirty working directory                          |
| 28 |              | `git stash list`                                 | List all stashed changes                                                |
| 29 |              | `git stash apply`                                | Apply stashed changes                                                   |
| 30 |              | `git stash pop`                                  | Apply and remove the latest stash                                       |
| 31 | Remote       | `git remote -v`                                  | Show remote connections                                                 |
| 32 |              | `git remote add <name> <url>`                    | Add a new remote repository                                             |
| 33 | Fetch        | `git fetch`                                      | Download objects and refs from another repository                       |
| 34 | Pull         | `git pull`                                       | Fetch from and integrate with another repository or a local branch      |
| 35 | Push         | `git push`                                       | Update remote refs along with associated objects                        |
| 36 | Tag          | `git tag`                                        | List tags                                                               |
| 37 |              | `git tag <name>`                                 | Create a new tag                                                        |
| 38 |              | `git tag -d <name>`                              | Delete a tag                                                            |
| 39 |              | `git push origin <tag>`                          | Push a tag to remote                                                    |
| 40 |              | `git push origin --delete <tag>`                 | Delete a remote tag                                                     |
| 41 | Reflog       | `git reflog`                                     | Show history of HEAD                                                    |
| 42 | Cherry-pick  | `git cherry-pick <commit>`                       | Apply the changes introduced by some existing commits                   |
| 43 | Bisect       | `git bisect`                                     | Use binary search to find the commit that introduced a bug              |
| 44 | Blame        | `git blame <file>`                               | Show what revision and author last modified each line of a file         |
| 45 | Clean        | `git clean -f`                                   | Remove untracked files from the working directory                       |
| 46 | Show         | `git show <commit>`                              | Show various types of objects                                           |
| 47 | Submodule    | `git submodule add <url>`                        | Add a new submodule                                                     |
| 48 |              | `git submodule update --init --recursive`        | Initialize and update submodules                                        |
| 49 |              | `git submodule sync`                             | Synchronize submodule URLs                                              |
| 50 | Help         | `git help <command>`                             | Get help for a specific Git command                                     |

