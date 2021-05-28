# Github GUIDE

### How to PUSH your folder to GITHUB
1. Create a new repository
2. Open Git Bash
3. Create your local project in your desktop directed towards a current working directory.
4. Initialize the git repository <br>
	- git init
5. Add the file to the new local repository.
	- git add . 
	- git status
6. Commit the files staged in your local repository by writing a commit message. <br>
	- git commit -m "upload"
7. Copy your remote repository's URL from GitHub.
8. Add the URL copied, which is your remote repository to where your local content from your repository is pushed. <br>
	- git remote add origin https://github.com/raymondk25/flutter-web/tree/master.git
9. Push the code in your local repository to GitHub <br>
	- git push -u origin master 
10. DONE!

### How to Clone your Repository from GITHUB
1. Select your Repository
2. Copy your HTTPS
3. Type on your CMD -> git clone "https://github.com/raymondk25/zhuanti.git"
4. DONE!

### How to UPDATE your folder to GITHUB
1. Select your folder
2. git status to check
3. git add .
4. git status check again
5. git commit -m "type your comment"
6. git push -u "https://raymondk25@gitwork.ypcloud.com/clouder-18/c18-raymond.git" master
7. DONE!

### How to create a Branch
1. git branch
2. git cheackout -b <new branch>
3. git add .
4. git commit -m "type your comment"
5. git push
6. git push --set-upstream origin development
