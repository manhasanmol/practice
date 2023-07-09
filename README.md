# practice
git remote add origin (respoitarylink) #to link local to remote
git push -u origin master       #all changes everthing to that respotary

# now for local 

git init #to initiliage that we will use all that things
git status #to check anythig need to commit or not
git add #to add things in a git res
git commit -m #to confirm a change after everything also message there
git log #to see all changes
git rm --cached -r .  #to remove before commit
git checkout #to undo before commiting the file in
git clone (link of git res) #to clone it on ur local

# if u do changes on github and not in local one while push u get an error so do this
git fetch origin # to take the changes from the github to local
git merge origin/master #to merge that changes ar a point and after that 
git push origin master # push the chages of local files now

# practice with branch 
git branch #to see on which branch u on
git branch <branch-name> #create one
git checkout <branch-name> #change from one to another add -b to switch to it 
git branch -d <branch-name> #Delete a branch (only if merged) or -D to force delete

# open source contribution
u can't make directly u need to first fork the repository 
after that will copy to your account do some changes or 
contribute, after if u want the person to adapt u need to pull
request, in network section that person can see your repository
in pull req u can tell real owner wht u contribute, in pull req of
owner he can see your pull req and review ur changes also can message u
or merge the changes.










make a .gitignore folder in which write the files that you don't want to commit while doing all
