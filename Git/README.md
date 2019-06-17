# Git and GitHub Training

## Project setup steps (as pertaining to git/github) 
1. Make new GitHub Repo
2. Make project folder on PC
3. Begin README.md
4. Git Init
5. Touch .gitignore
6. Add *.code-workspace to .gitignore
7. Git add .
8. Git Commit -m 'Initial Commit'
9. Git remote add origin https://github.com/RJ-Easter/Training.git
10. Git push --set-upstream origin master or git push -u origin master
* Setup Complete at this point.
* Follows: Steps while working on project.
11. Begin work on project
12. Save locally when done working
13. Git add .
14. Git commit -m 'Note about work completed'
15. Git push

## Questions
* What is: git push --set-upstream origin master ? (After doing this, a simple git push worked.)
* Why is GitTraining.code-workspace still in the online repo after adding *.code-workspace to .gitignore?
* Does deleting a file from the online github repo also delete it from your local repo after a git push?

## Answers
* GitTraining.code-workspace is still in the repo, because it was pushed on the initial commit. Then *.code-workspace was added to .gitignore and has since not been updated. 
* Deleting from the github repo requires a git pull from your local work space. This deletes the file from your local repo, then you can git push again.
* The initial push to the remote repo should have the flag -u (which means --set-upstream).