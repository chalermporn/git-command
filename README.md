# git-command

…or create a new repository on the command line

```sh
echo "# git-command" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/chalermporn/git-command.git
git push -u origin master
```
…or push an existing repository from the command line

```sh
git remote add origin https://github.com/chalermporn/git-command.git
git push -u origin master
```

## How do I delete a Git branch both locally and remotely?

To remove a local branch from your machine:

```sh
git branch -d {the_local_branch} #(use -D instead to force deleting the branch without checking merged status)
```

To remove a remote branch from the server:

```sh
git push origin --delete {the_remote_branch}
```
