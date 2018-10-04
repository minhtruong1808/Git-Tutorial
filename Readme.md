# Command Prompt Navigation 


touch : creating new files manually (only works on Git Bash)<br/>
Dir : Directory, show all contents on current path<br/>
cd : change directory, go to directory<br/>
cd.. : Move backward<br/>

## Once
Git init : Initialize Version control<br/>
Git remote add origin git@github.com:User/UserRepo.git : Connect the Directory to repository <br/>
Git remote -v : To check if the Directory and Repository are really connected <br/>

## Updating
git add .: add all files and changes to the staging area in order to be commited<br/>
git commit -m"" : Commit the directory along with a messeage<br/>
git push origin : Push all changes from all local branches to mathcing branches the origin remote<br/>
git push origin master : push changes from the local master branch to the remote master branch<br/>