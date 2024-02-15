# Git-github-Tutotrila
Git/Github tutorial
<br>
Author - Akshay Bharat Sonawane B.E.(IT)

//
1. untracked - new files that git doesn't tracked yet
2. modified - changed
3. staged - file is ready to commit
4. unmodified - unchanged

//
add & commit <br>
add - adds new or changed files in your working directory to the git staging area.<br>
git add <file-name><br>

commit - it is the record of change<br>
git commit -m "some message"<br>

//
push - upload local repo content to remote repo<br>
git push origin main<br>

//
init command<br>

init - used to create a new git repo<br>
git init<br>
git remote add origin <-link-><br>
git remote -v  (to verify remote)<br>
git branch (to check branch)<br>
git branch -M main (to rename branch)<br>
git push origin main<br>

//
Branch commands<br>

git branch (to check branch)<br>
git branch -M main (to rename branch)<br>
git checkout <-branchname-> (to navigate)<br>
git checkout -b <-branchname-> (to create new branch)<br>
git branch -d <-branchname-> (to delete branch)<br>

//
Merging code <br>

1 way - 
git diff <-branch-name-> (to compare commits, branches, files & more)<br>
git merge <-branch-name-> (to merge two branches)<br>

2 way - create a PR<br>
PR - Pull Request - It lets you tell others about changes you have pushed to a branch in a repository on GitHub.<br>

//
Pull Command<br>

git pull origin main<br>
used to fetch and download content from a remote repo and immediately update the local repo to match the content.<br>