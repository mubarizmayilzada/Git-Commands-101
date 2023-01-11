# Git-Commands-101
Welcome to the ultimate guide to Git commands! Whether you're a seasoned pro or just getting started with version control, this repository has something for everyone.

Git can be a bit intimidating at first, but once you get the hang of it, it's like mastering a new skill. In this repository, you'll find a comprehensive list of Git commands, along with explanations and examples of how to use them.

## Basic Commands
- `git init` - This command initializes a new Git repository and prepares it for version control.
- `git clone` - This command allows you to create a local copy of a remote repository on your machine.
- `git status` - This command allows you to check the status of your current repository, including which files have been modified.
- `git add` - This command stages files for the next commit.
- `git commit` - This command saves changes to the repository.
- `git log` - This command allows you to view the commit history of the repository.

## Branching and Merging
- `git branch` - This command allows you to create and list branches in the repository.
- `git checkout` - This command allows you to switch between branches.
- `git merge` - This command allows you to combine changes from one branch into another.
- `git branch -d <branch_name>` - This command allows you to delete a branch

## Working with remote Repository
- `git remote -v` - This command allows you to list all remote repositories linked with the current repository
- `git push` - This command allows you to send local changes to a remote repository.
- `git pull` - This command allows you to retrieve changes from a remote repository and merge them into the local repository.

As you can see, git commands can be quite simple if you approach them systematically, so don't be afraid to dive in and start experimenting with different commands. And remember, with git, you can always undo mistakes.

## Collaboration
- `git fetch` - This command allows you to retrieve remote changes without merging them. This is useful for reviewing changes before merging them into your local repository.
- `git pull --rebase` - This command allows you to retrieve remote changes and reapply your local commits on top of them, rather than merging them. This can help avoid merge conflicts.
- `git push --force` - This command allows you to force push changes to a remote repository. This can be useful if you need to overwrite remote changes that you do not want to keep. However, it is also dangerous, as it can cause loss of work, so use this command with caution.

## Stashing
- `git stash` - This command allows you to temporarily save changes that you are not ready to commit. You can later apply these changes using `git stash apply`. This can be useful if you need to switch branches to work on something else, but don't want to commit your changes yet.
- `git stash list` - This command allows you to list the available stashes.
- `git stash apply` - This command allows you to apply a specific stash.

## Tagging
- `git tag -a <tagname> -m <message>` - This command allows you to add an annotated tag to the repository. Annotated tags are more informative than lightweight tags, as they include metadata such as the tagger's name and email, and the tag message.
- `git tag -d <tagname>` - This command allows you to delete a tag from the repository.
- `git show <tagname>` - This command allows you to display information about a tag.

## Reverting
- `git revert <commit-hash>` - This command allows you to revert a specific commit, by creating a new commit that undoes the changes made in the original commit.
- `git reset <commit-hash>` - This command allows you to reset the repository's state to a specific commit. This can be useful if you want discard commits that have not been pushed yet.

And always remember, with great power comes great responsibility, use git wisely!
