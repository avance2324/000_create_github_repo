Overview
====================
 test how to create repository in github and push local repository to github

How to
====================
1) sign in github with account 2324avance
2) create repo: 000_create_github_repo
3) create create local git repository for this directory:
     git init
4) add and commit to local repository
5) add a new remote git repository as a shortname
     git remote add origin <url> ## get url of 000_create_github_repo from github
6) push branch master to remote
   git push --set-upstream origin master ## origin is shortname of url of repo in github
     
