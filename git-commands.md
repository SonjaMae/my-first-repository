# Git on the Command Line

We can use the git version control application directly from the command line. Here are some useful commands to get started.

- `git init` Creates a git repository in the current folder. Don't nest one git repository folder inside of another.
- `git status` Gives the current status of your git repository.
- `git add .` 'Stages' all current changes so they're ready to be committed.
- `git commit -m "Your Message"` Take all staged changes and create a snapshot of the current state of your repository. Using commits is how we generate a *commit history* for our repository. Try to make your message under 50 characters if possible.
- `git pull` Grab any changes from your remote repository (e.g. GitHub.com) and pull them down onto your local repository (the one on your computer).
- `git push` Takes whatever commits you have on your computer and push them to the remote repository.
- `cls` Clears terminal screen.

There are a lot of things to learn when it comes to working with git, but these commands are the day-to-day ones that you will do when working with version control.

**TIP:** You should make frequent, small commits when working on your projects.

Work with these commands every day, and they will become a part of you.


...
## Remote Repositories

You can use the GitHub CLI to create a remote repository on GitHub.com.

```shell
gh repo create my-first-repository
```
Creates a new GitHub repository.

You can **push** your code by typing
```shell
git push -u origin master
```

After that, type `git push` to push any local changes to the remote repository.

Here's some other helpful commands with regard to the remote repository connections for your local repository.

- `git remote -v` View all the remote repositories.
- `git remote remove [remoteName]` Remove a remote entry.
- `git remote add [remoteName] [URL-to-repository]` Add a remote repository.