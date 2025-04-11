![IMG20231005175128edit](https://github.com/user-attachments/assets/eff7eff7-41a3-4afe-bacc-0d5f30085bd8)ensure that the repository is not currently on the branch to be deleted 
1-delete branch locally 
``sh
git branch -d branch-to-delete 
2-delete branch remotely 
``sh
git push remote-name --delete branch-to-delete
<br>
annotated tags vs lightweights tags
Annotated tags are full objects in Git's database. They contain metadata such as the tagger's name, email, date, and a message.
<br>
git tag -a v1.0 -m "Release version 1.0"
<br>
lightweight tags
Lightweight tags are simply pointers to a specific commit. They do not contain any additional metadata.
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



![Alt text]([url_to_image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.choice.com.au%2Felectronics-and-technology%2Fcomputers%2Fdesktop-and-laptop-computers%2Fbuying-guides%2Fdesktop-computers&psig=AOvVaw3VD7D8Jp-wLSgj2v2WVxMP&ust=1744462353206000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMjV5OqC0IwDFQAAAAAdAAAAABAE))






