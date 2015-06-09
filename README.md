testing branches using git

 We can’t automatically merge this pull request.

to resolve conflicts before continuing.
Checkout via command line

If you cannot merge a pull request automatically here, you have the option of checking it out via command line to resolve conflicts and perform a manual merge.

Step 1: From your project repository, check out a new branch and test the changes.

git checkout -b slidep-patch-2 master
git pull https://github.com/slidep/branches.git patch-2

Step 2: Merge the changes and update on GitHub.

git checkout master
git merge --no-ff slidep-patch-2
git push origin master
