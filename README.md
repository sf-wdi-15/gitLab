Git & Github Lab
================

Motivation
----------

The intention of this lab is to "git" you comfortable with using the version control system [Git](http://en.wikipedia.org/wiki/Git_\(software\)) and [Github](https://github.com). We will walk through a typical workflow using these tools. 


Before getting started, you need to set up your SSH keys with Github. If you haven't set them up yet, follow the steps on Github's guide, [Generating SSH Keys](https://help.github.com/articles/generating-ssh-keys/).

Lab
---


### I. Fork this Repository

Find the button at the top of this page labeled **Fork**. When you click it, Github creates a copy of the repository in your own account. You can freely make changes on this copy without affecting the original repository. Clicking on it will 'fork' the repository, giving you a copy of it that's yours.


### II. Clone the Repository Locally

Now that you've got your own copy of the repository in your Github account, make a clone of it on your computer. That way you can make changes locally, before pushing them to the remote repository on Github.

##### Hint
```bash
git clone PUT_THE_REPO_URL_HERE
```

### III. Checkout a New Branch

In your terminal, change into the directory where you cloned the repo. Checkout a new branch. You can name it whatever you'd like. This branch will your development branch, where you can make changes while keeping the original verison on the master branch.

##### Hint
```bash
git checkout -b BRANCH_NAME
```

This command is just shorthand for ```git branch BRANCH_NAME``` followed by ```git checkout BRANCH_NAME```.

### IV. Make Some Changes
Now that you're on a branch other than master, make an ```about_me.html```. You can edit the content to be whatever you'd like, but be creative. Maybe use something like [this](https://github.com/sf-wdi-14/notes/blob/master/lectures/week-1/about-me-pages/dennis.html) as a template.

### V. Add the Changes
Once you've finished making any changes you'd like, add those changes to Git. This tells Git that these are changes you'd like to record on your next commit. If you aren't sure what you changed, you can check by using ```git status```.

##### Hint
```git add THE_CHANGES_YOU_MADE```.

### VI. Commit the Changes
With all of your changes made, it's time to commit them! Commiting adds your changes to the Git log and let's you see what you changed.

##### Hint
```bash
git commit -m "PUT YOU MESSAGE HERE."
```

I personally like to have it start with a present tense action verb. Think of something along the lines of: 'add new aboutme html page'.

### V. Push Your Changes to Github

Push the changes on your branch to your remote repository.

##### Hint

```bash
git push origin YOUR_BRANCH_NAME
```

### VI. Make a Pull Request on the Original Repository

Go to github and make a pull request. This is a request to merge your changes into the master branch in the original repository. Your changes can be reviewed, commented on, and updated before they are integrated into the main code.


## Now that you're done...
Take a chance to look over this blog post on [merge conflicts in git](http://www.choskim.me/when-do-merge-conflicts-occur-in-git/). The author of the blog post is Cho Kim a WDI instructor here.

Also feel free to check out this [dev handbook](https://github.com/Clever/dev-handbook/blob/git-commit-style-guide/git-workflow.md).
