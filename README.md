#Git & Github Lab
The intention of this lab is to git you comfortable with using git and github by walking you through a typical workflow using the tools. Before you get started [make sure you've set up your SSH keys with Github](https://help.github.com/articles/generating-ssh-keys/)

##Fork this Repository
Up at the top of this page there's a button that says **fork**. Clicking on it will 'fork' the repository, giving you a copy of it that's yours. This gives you the authority freely make changes without effect the original repository.

##Clone the Repository locally
Now that you've got your own copy of the repository you can make a clone of it on your computer, so that you can make changes locally before pushing them to the remote repository.

Hint: ```git clone PUT_THE_REPO_URL_HERE```

##Checkout a new branch
Change into the directory that you cloned and checkout a new branch. Name it whatever you'd like.

Hint: ```git checkout -b BRANCH_NAME```, which is just shorthand for ```git branch BRANCH_NAME``` followed by ```git checkout BRANCH_NAME```.

##Make some changes
Now that you're on a branch other than master, make an ```about_me.html```. Be creative, maybe use something like [this](https://github.com/sf-wdi-14/notes/blob/master/lectures/week-1/about-me-pages/dennis.html) as a template.

##Add the changes
Since we've finished making all the changes we needed, add those changes to git. If you arent sure what you changed you can check by using ```git status```.

Hint: ```git add THE_CHANGES_YOU_MADE```.

##Commit the changes
With all of our changes made, its time to commit them!

Hint: ```git commit -m "PUT YOU MESSAGE HERE."```. I person like to have it start with a present tense action verb. Think of something along the lines of: 'add new aboutme html page'.

##Push them to Github
Push it to your remote repository.

Hint: ```git push origin YOUR_BRANCH_NAME```

##Make a Pull Request to the original repository
G



##Now that you're done...
Take a chance to look over this blog post on [merge conflicts in git](http://www.choskim.me/when-do-merge-conflicts-occur-in-git/). The author of the blog post is Cho Kim a WDI instructor here.