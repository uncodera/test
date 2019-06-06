# test
test repo


first line

git clone url

git status


#add the file 
git add filename
  
git commint -m 'comment'

git log


push to global change
git push 


undo the unstaged file  or
If you have modified a file in your working tree, but haven't committed the change, then you can use git checkout to checkout a fresh-from-repository copy of the file.

git checkout -- filename

undo the commited file 
git log
git revert keyid



# go the particalar commit id
git reset 


baranch exepriment and mearge
to list all branch  * active
git branch 

create branch 
git branch branchname


switch to branch

git checkout branchname

make changes into master branch
go to master branch
git checkout master

merger thirsy into master
git merge thirsty


to push the other branch 

git push --set-upstream origin thirsty


create branch and switch 
git checkout -b branchname2

delect the branch 

git branch -d branchname2


download the other branch

 git fetch origin other-branch
 
 and merge it
 git merge origin/other-branch
 git commit    # And commit the merge!


git rest [commit]
#it will undo all commits after this commit

git reset --hard [commit]
#discard all history and changes back to the sepcified commit




#Two people working on a file at the same time in git [duplicate]

the procedure should be the below:

pull the file
edit it
commit it(it commits to your local repository)
pull it again (if there are any conflict you will Be notified) in that case you can solve it executing the below command(GitBash on your repository working folder):

git mergetool

it will run the merging tool you got configured in your .gitconfig file

after that you can push your changes

Your working copy and staging area:
git diff
Staging area and the latest commit:
git diff --staged
Your working copy and commit 4ac0a6733:
git diff 4ac0a6733
Commit 4ac0a6733 and the latest commit:
git diff 4ac0a6733 HEAD
Commit 4ac0a6733 and commit 826793951
git diff 4ac0a6733 826793951




so he uses the git show command to review his changes.

git show d1e19d316224cddc437e3ed34ec3c931ad803958






