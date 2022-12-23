# git-cheat-sheet

Personal cheat sheet for common Git Commands


## Initializing

|         **Command**           	|                                               **Desciption**                                              	|
|:--------------------------------------   |:---------------------------------------------------------------------------------------------------------	|
| ```git clone <remote_repo_url> ``` | clone a repository using remote hosts such as GitHub, GitLab, DagsHub, etc (using HTTP or SSH sntax) 	|
| ```git init```                 	| initialize git tracking inside the current directory                                                      	|

## Adding and modifying files

|              **Command**              	|                                                                     **Desciption**                                                                     	|
|:-------------------------------------	|:------------------------------------------------------------------------------------------------------------------------------------------------------	|
| ```git status ```                        	| show which files are in the staging area                                                                                                               	|
| ```git add [filename]  ```                  	| add a file to the staging area                                                                                                                         	|
| ```git reset [filename] ```             	| remove a file from the staging area                                                                                                                    	|
| ```git diff  ```                      	| show all the changes in the repository                                                                                                                 	|
| ```git diff -r HEAD ```                  	| compare state of the file with those in the staging area (-r flag means "compare to a particular version" and HEAD refers to "the most recent commit") 	|
| ```git commit -m "[message]"  ```          	| save the changes in the staging area                                                                                                                   	|
| ```git commit --amend -m "[new message]" ```	| change an accidentally mistyped commit message                                                                                                         	|

## Logging and viewing history

|       **Command**       	|                                      **Desciption**                                     	|
|:-----------------------	|:---------------------------------------------------------------------------------------	|
| ```git log```                 	| view the log of the project's history (log entries are shown most recent first)         	|
| ```git show [commit hash] ```  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| view the detials of a specific commit (using first few characters of the commit's hash) 	|
|```git annotate [filename] ```	| show who made the last change to each line of the file and when                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

## Pulling pushing

|              **Command**              	|                  **Desciption**                  	|
|:-------------------------------------	|:------------------------------------------------|
| ```git pull [remote branch]  ```       	| pull changes from the remote branch              	|
| ```git push [remote name] [ branch name] ```	| push changes made locally to a remote repository 	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|


