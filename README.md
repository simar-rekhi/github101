# Simar's GitHub 101

## Setting Up `git`
- install Git: https://git-scm.com/
- Configure your name/email: `git config --global user.name "Your Name"` and `git config --global user.email "you@example.com"`

## Creating a New Repository
- Start by creating a project folder locally. For the purpose of this workshop, let us assume you decide to call it `github101`
- Open terminal for this directory, and initialize the folder by typing: `git init`
- Open GitHub and create an empty repository
- Navigate to the ` <> Code` section, and copy the HTTPS link
- Head back to the Terminal and type out the following command: `git remote add origin <url from the step above>` <br> Quick Tip! To check your connection try typing `git remote -v` and notice the output.

## Add. Commit. Push
- Create a toy file in your project folder, say, `hello.py ` or `README.md`
- Use the following commands: `git add .` followed by   `git commit -m "type in a message"` followed by `git push -u origin <branch name>`
