# workflow and branching

## create topic branch
1. % cd /path/to/working/copy 
2. % git checkout dev 
3. % git pull 
4. % git checkout -b ‘<topic name>(<issue id>)’
5. modify and commiting.
(modifing…) 
6. % bundle exec rubocop (fix indicated points if exists) 
7. % git add /path/to/changes 
8. % git commit ( commit comment: should be the basecamp ticket url ) 

## rebase. 
1. % git fetch origin 
2. % git rebase origin/dev (resolve conflicts if need)
push and pull requests
3. % git push origin ‘<topic name>(<issue id>)’ (create pull request on GitHub)   

## make patch
1. make patch which can make commutable changes of your work to master. 
2. post it to the corresponding basecamp ticket.
