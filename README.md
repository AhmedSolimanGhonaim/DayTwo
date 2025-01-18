# DayTwo
iti day two repo



******************


Delete Local Branch
To delete the local branch

git branch -d <branch_name>
git branch -D <branch_name>

Delete Remote Branch
$ git push <remote_name> --delete <branch_name>


***********************

annotated git tag -a v1.2 -m "my version 1.4"

light weight git tag v1.2

list all tags    git tags

*************
delete tags locally and remotly 
locally $ git tag -d <tag_name>
remotly $ git push --delete origin tagname


![image](https://th.bing.com/th/id/OIP.mtupwKQy9UabTdHvByomDQHaEo?rs=1&pid=ImgDetMain "naruto")



*******************************
rebase ::
Rebase is used when you want to integrate changes
 from one branch into another in a linear fashion. 
 It is especially useful for cleaning up commit history and making it easier to follow. 
 Common scenarios include updating a feature branch with changes from the main branch, or combining several small commits 
 into a single commit before merging. However, avoid rebasing public branches,
  as it can rewrite history and cause issues for others.
  use cases :
  Linearizing History: Rebase helps maintain a clean project history by creating a linear sequence of commits, making it easier to follow the project timeline.
Incorporating Changes: Developers often use rebase to apply changes from the main branch into their feature branches, ensuring they are up to date with the latest code without creating unnecessary merge commits.
Conflict Resolution: It can be employed to resolve conflicts when integrating branches, allowing for a more controlled approach to resolving differences as commits are applied individually.