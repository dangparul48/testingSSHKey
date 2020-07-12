# This is repo is for the notes of Git command line tutorials

## Generating SSH Keys for github

```bash
ssh-keygen -t rsa -b 4096 -C "email"
```
In the above command, -t is for type, -b is for bytes and -C is for comments

## Major Git commands

```bash
git clone repolink	# This command is used to clone an existing git repo
git add files		# To add the modified files for commit
git commit -m "msg"	# To commit the changed files
git push		# To push the files to the git server
git branch		# To know the current branch where you're in
git status		# To know the status of git branch/repo
git checkout -b "bname"	# To create a new branch and switch to it
git pull		# To pull the changes from the git repo
```


