# Demo
Hello. This is my first repository.
<br>
This is step by step process for me to learn github.
<br>
steps:
<br>
1.install gitbash and vscode
<br>
2.check in terminal (git --version)
<br>
3.open gitbash and type (git config --global user.name "username of github"
                        git congig --global user.email "user gmail of github")
<br>                     
4.open a new folder of GITDEMO in vscode open the terminal just type git --version to check again 
<br>
Now comes methods 
<br>
1. clone : git clone (link)...link is from github in the repository click code and select https link and paste in vscode.
<br>
2. ls : ls ...for checking number of files. (didnt worked for me..??)
<br>
3. status : git status ... the result would be (modified,untracked,staged(if we add modified or untracked then it is given as staged i.e.; ready to be committed),unmodified)
<br>
4. add : git add <filename> (git add . --> for adding all changes)
<br>
5. commit : git commit -m "write si=omething here"
<br>
6. push local content to remote : git push origin main
<br>
7. mkdir "dirname" for creating new folder. 
<br>
8.git init : initialise git repo.
<br>
9. create a new repo in github. (git remote add origin <link>) , (git remote -v) , (git branch) , (git branch -m (name))
<br>

COMPLETED .
<br>
Basic flow : github repo -> clone -> changes -> add -> commit -> push
<br>

BRANCH COMMANDS
1. git branch, git branch -m main(any name insgtead of main can be used), git checkout <branchname>(to navigate), git checkout -b <new branchname>(to create new branch), git branch -d <branchname>(to delete).
<br>
2. git checkout main , (git pull origin main - pull request to merge) , (git merge main - to merge)
 <br>
 
UNDOING CHANGES
<br>
1. Staged changes : git reset <filename> or git reset
<br>
2. commited changes (for 1 commit) : git reset HEAD~1
<br>
3. committed changes (for multiple commits) : git reset <commit hash(get by git log)> , git reset --hard <commit hash>
<br>
FORK - used to copy entire code and work on it.
