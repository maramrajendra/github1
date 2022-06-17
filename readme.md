Link local gitrepo to github.

1) Create a new repository on GitHub.com.
2) Open Git Bash.
3) Change the current working directory to your local project.
4) git init -b main
above command initializes the local directory as git repository and makes current directory as main branch.
5) git add . && git commit -m "First commit"
6) it remote add origin  <REMOTE_URL> 
git remote add origin https://github.com/maramrajendra/github1.git
7) git remote -v
origin  https://github.com/maramrajendra/github1.git (fetch)
origin  https://github.com/maramrajendra/github1.git (push) 
8) git push origin main