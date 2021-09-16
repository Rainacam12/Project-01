# Git Workflow Guide

## in terminal
1. `git pull origin master`
2. `git checkout -b RC/d-0001`
3. work on single feature like header
4. `git add example.file directory`
5. `git commit -m "PROJECT-1-0001: feature you added"`
6. `git push origin RC/d-0001`
7. `git checkout master`

## in github
1. create pull request (big green button)
2. merge pull request
3. delete branch

## in terminal
1. `git pull origin master`
2. `git branch -d RC/d-0001`
3. `git checkout -b RC/d-0002`
4. **REPEAT**