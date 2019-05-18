# MergesVsRebase
This is meant as an example of what merging does versus what rebasing does, as well as including how to do either.

Scenario One : Creating a new branch, editing it, and pushing it to the remote repository.
                Create a new branch that looks just like master.
                Tell git that you made a change with git add
                Commit the changes you made, which 

Commands used:
git checkout master
git pull
git checkout -b scenario-1
git status
git add README.md
git status
git commit
git push origin HEAD

After this you raise a merge request in git lab or whatever git hosting webservice you want.