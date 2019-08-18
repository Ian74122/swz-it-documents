# git rules in IT team

### Set Up
####same with your name in this team
```
git config --global user.name "Your Name" 
git config --global user.email "your@email.com" 
```

### IMPORTANT
- DON'T DO ANYTHING IN MASTER BRANCH
- DON'T DO ANYTHING IN MASTER BRANCH
- DON'T DO ANYTHING IN MASTER BRANCH

### git commands
- git pull
- git push
- git checkout [branch-name]
- git reset [sha1|HEAD|HEAD^]
- git add [file | .]
- git status
- git commit -m "commit message"

### branch name rule
- "feature/this_is_a_description_for_feature"
- "hotfix/this_is_a_description_for_hotfix"

### workflow for new feature
1. git checkout master
1. git pull
1. git branch 'feature/xxxxxxxx'
1. finish your feature from issues , one ticket one branch
1. all commit message have meaning and readable , don't write any message I can't understand.
1. one(or least) of commit message in the branch , you should use github keyword, fix #1 (# + issue number in github)
1. git push to remote
1. send pull request and message superior
