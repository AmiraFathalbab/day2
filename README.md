ensure that the repository is not currently on the branch to be deleted
1-delete branch locally
``sh
git branch -d branch-to-delete
2-delete branch remotely 
``sh
git push remote-name --delete branch-to-delete


