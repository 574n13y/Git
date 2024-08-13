# Commands

Set global username and email for Git (Locally).

```sh
git config --global user.name "<your username>"
git config --global user.email "<your email>"
```

Initialise an empty Git Repository

```sh
git init
```

Clone an existing Git Repository

```sh
git clone <repository URL>
```

Add file/stage to git

```sh
git add <filename>
```

Add all the files to git

```sh
git add .
```

Commit all the staged files to git

```sh
git commit -m "<your commit message>"
```

Restore the file from being modified to Tracked

```sh
git restore <filename>
git checkout <filename>
```

Show the status of your Git respository

```sh
git status
```

Show the branches of your git repository

```sh
git branch
```

Checkout to a new branch

```sh
git checkout -b <branch name>
```

Checkout to an existing branch

```sh
git checkout <branch name>
```

Remove a branch from Git

```sh
git branch -d <branch name>
```

Show remote origin URL

```sh
git remote -v
```

Add remote origin URL

```sh
git remote add origin <your remote git URL>
```

Remove remote origin URL

```sh
git remote remove origin 
```

Push your local changes to remote branch

```sh
git push origin <branch name>
```

Pull your remote changes to local branch

```sh
git pull origin <branch name>
```

Check you git commits and logs

```sh
git log
```
