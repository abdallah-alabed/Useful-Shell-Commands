# Useful commands for developers in Git Bash
1. **git init** : initialize local repo
2. **git add** : add files to index
    - git add . : add all to index
    - git add *.html : add all files that have .html extension to the index
3. **git status** : show added/not-added files in the staging area
4. **git commit** : commit changes to index 
   - git commit -m "Message": commit with comment (the correct way to commit)
5. **git push** : push committed changes to the remote repo
   - git push -u origin master
6. **git pull** : pull changes from remote repo
7. **git clone** : clone repo from remote repo to local repo
8. **git --version** : show git version on local device
9. **git config --global user.name "NewName"** : set name for author
10. **git config --global user.email "Email"** : set email for author
11. **git rm --cached (file)** : remove file from staging area
12. **git checkout** : move/create new branch
13. **git merge** : merge changes between branches
14. **git remote** : list all remote repos
   - git remote add <name> <path>: add remote repo with the name
15. **git config --global --add safe.directory (path)** : allow git commands in this pc user