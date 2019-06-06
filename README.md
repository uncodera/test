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











