# Good Git and GitHub Links

To learn about GitHub you should try the [hello-world exercise](https://guides.github.com/activities/hello-world/).

This file is created using the GitHub flavor of markdown.  Here is a link to the [https://guides.github.com/features/mastering-markdown/](cheatsheet).

Here are some more good links to learn more about Git and GitHub:
* [https://guides.github.com/introduction/git-handbook/](Git Handbook)
* [https://guides.github.com/introduction/flow/](Learning about branching)
* [https://help.github.com/articles/resolving-a-merge-conflict-on-github/](How to for merge conflicts)

## Typical workflow
1. `git clone git@...`
   * this is a one time thing.  you are essentially cloning down the project/repo to your local machine
2. `git checkout -b branch name`
   * You don't want to work off your master, but create a new branch to work you changes on
3. edit your files
   * this is you doing your work in the code
4. `git add file names` or do `git add .`
   * with this command you are saying I'm ready to check in/stage these files.  If you use a <.> that means you are checking in every file that has been updated
5. `git commit -m "commit message here"`
   * this is the message that you are communicating why you changed the files you are about to push back up to GitHub
6. `git push origin branch name`
   * this is where you are delivering the files you have checked in/staged back up to the branch in GitHub
7. Create a GitHub merge Request
   * the files you have updated are now in the branch on GitHub, but you want them to get merged back into Master.  Therefore, you need to request a "Pull Request" in GitHub
8. `git pull origin branch name`
   * some times work will still be occurring in the branch after you pushed your changes up to GitHub.  Then you would skip step 7 and pull down all the changes that have been put into that branch.  this is the command that pulls down the files again from GitHub


## Things to demo
* What a repo is
* GitHub desktop
  * explain about command line options
* Create branch
* Show a clone down to workstation, do an update, and push back to GitHub
* Show a merge conflict
* Show Issue board
