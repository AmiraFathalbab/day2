ensure that the repository is not currently on the branch to be deleted 
<br>
1-delete branch locally 
<br>
git branch -d branch-to-delete 
<br>
2-delete branch remotely 
<br>
git push remote-name --delete branch-to-delete
<br>
annotated tags vs lightweights tags
<br>
Annotated tags are full objects in Git's database. They contain metadata such as the tagger's name, email, date, and a message.
<br>
git tag -a v1.0 -m "Release version 1.0"
<br>
lightweight tags
Lightweight tags are simply pointers to a specific commit. They do not contain any additional metadata.
<br>
when to use rebase:<br>
Keeping Feature Branches Updated:
<br>
git checkout feature-branch
<br>
git rebase main






<br>
git tag v1.0
<br>
when to use rebase:

how to list tags:
<br>
git tag
<br>
Delete a Local Tag:
git tag -d tagname
<br>
Delete a remote Tag:
git push --delete remote-name tagname


![computer](https://img.choice.com.au/-/media/dc5a904b4e20498da3c70c268b3b197b.ashx?w=760)








