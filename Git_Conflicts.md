# How to resolve git conflicts
## Merge conflicts
> In case an error occurs, 
1. Type `git pull origin master` to pull all the changes
2. Edit the contents first and then save
3. Type `git add .`
4. Type `git commit -m {{name}}
5. Type `git pull origin master`
## Branch conflicts
> In case an error occurs,
1. Type `git switch master` to check your current path
2. Make sure you work on master 
3. Edit the contents and save
4. Type `git add .`
5. Type `git commit -m {{name}}
6. Type `git pull origin master`
7. If you would like to see its graph, `git log --oneline --graph`