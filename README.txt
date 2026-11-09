'git init -> powers your folder to be managed by git and initiliazes a new empty reposirtary
-> also creates .git folder that has all the relevent logic to manage versions of your logic 


'working area' -> bunch of files that are not currently handled by git 
it means that chnages done or to be done are not managed by git yet. a file managed which is is 
working area is considered to be not in the statging area when we do git status and we see bunch of untracked files then 
this are actually called  wokring area 


'statging area' -> what all files are going to be part of the next version that will be created
is the place where git knows what chnages will be done from the last version to next version


'reposirtary area' ->  this area actually contains the details of all your previoius registered project 
the files in this area git manages them and knows their versions history 


'git add <filename>' -> moves file from wokring area to statging area


'git rm --cached <filename> ' -> moves file back from statgiing area to working area 


'commit' -> one version (simple terms)
is a particular version of the project it captures the snapshnot of the project staged changes 
and creates a verions out of it 


'git commit ' -> registers statging changes to a commit


'git log' -> list down all the commits of the repositary if you want to exit out of git log prompt 'q'


'git restore <file_name>' -> deleted all the which is in the staging area but not yet commited
this can be useful if we did some dirty peice of code and no more wanted 
// instead of deleting line line we can do this restroe 
// restores to last version of it 


'git restore --staged <file_name> -> it removes file from changes from staggin area to working area
this only works if changes are in your paging area 



difference between git rm and git restore 



// green bar in vs code means chnages are in wokring area 
// not showing green bar changes are in staging area 



'git rm --cached <file_name> ' -> if we want to whole file to move back to untracked state then do git rm 
if we just want changes to be moved in wokring area or staging area then we do git restore 
