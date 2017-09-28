# This is our first repo

### Git is very useful for version contorol and collaboration

#### The common workflow with git is:
* git init -> to create a new local repository
* create and/or modify files
* git add <files> -> to stage them to your local git repository
* git commit -m -> to commit your changes to your local repository
* create a repository on Github if one does not exist
* git remote add <repo_name> <repo_url>
* git push -u origin master

#### To Create a branch
* from the master branch use "git branch <new_branch_name>"
* git checkout <new_branch_name?
* EASIER Method is to git checkout -b <new_branch_name?" which creates the branch and checks it out at the same time
* to push a branch to remote repo, "git push <remote_name> <branch_name>"
* ie, git push ryan ryan_branch_1

#### To Merge a branch back onto master:
* when you're done working on your feature branch
* git checkout master
* git merge <your_feature_branch_name>
* there will be a merge comment page that you'll have to save
* git push origin master (will push your merged changes to master)

#### To add a second remote repo:
* git remote add <name> <url>
* ie, git remote add ryan https://github.com/rdesmond/my_repo
* to push to second remote, "git push <remote_name> <branch_name>"
* ie, git push ryan ryan_branch_1
