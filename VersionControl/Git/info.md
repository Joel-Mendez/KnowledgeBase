# Git
Git is a distributed version control system (VCS) to aid in the tracking of changes in a software project, not just across time, but across collaborators. 

## Installation
MacOS (using homebrew): ```brew install git```

Verify Installation: ```git --version```

## Initialization 
To initialize a local git repo, navigate to project direcotry and enter:
```git init ```


## Staging and Commiting Changes
Stage a change:
```git add -a filename.txt```

Commit: ```git commit -m "message" ```

## Checking Status
Get the status of your current branch: ```git status```

## GitHub Integration
Linking your local repo to a GitHub repository: 
```git remote add origin url```

Pushing to remote GitHub repo: ```git push origin branch_name```

Verify: 
```get remote -v```