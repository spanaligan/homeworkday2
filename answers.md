Sarah's answers to the following questions:

What command do you use to setup a git repository inside of your folder?
git clone <insert the copied URL from GitHub>

What command do you use to ask git to start tracking a file?
git add . (the dot allows you to add all changed files)

What command do you use to ask git to move your file from the staging area to the repository?
git commit -m "message about your changes" followed by git push origin master

What command do you use to get updates from the class repository?
git fetch upstream

What command do you use to push your work to your fork of the class repository?
git push upstream master (upstream because the 'origin' is not your place)

Additional questions:

What command do you use to unstage a file?
git reset -- <file name> 

What command do you use to change your files back to how they were after a commit?
git revert HEAD

Why is it important to use -- when changing files back to a previous state?
The -- is used when undoing something in git 

Why might you want to reset your files back to a previous commit?
If you have committed something incorrectly or with mistakes that break your code, you may want to revert back to an
 earlier version that
 was working.