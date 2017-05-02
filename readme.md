## To create a local repo:
``` 
    git init 
```

## To add local changes:
``` 
    git add . 
```

## To commit local changes:
``` 
    git commit -m "msg"
```

## To add remote repo:
``` 
    git remote add url
```

## To push to remote repo:
```
    git push origin <branch_name>
```

## To clone a repo:
```
    git clone url
```

## To create separate branch:
``` 
    git branch <branc_name>
```

## To use other branch
```
    git checkout <branch_name>
```

## To merge branches locally:
```
   git checkout master
   git merge merge <branch_name>
```

## To push branch to remote repo:
```
    git push --set-upstream origin <branch_name>
```

## To pull changes and update repo locally and remotely:
```
    git fetch
    git checkout <branch_name>
    git checkout master
    git merge <branch_name>
    git push origin master
```
