### Delete, remove directory
``` shell
rmdir /S /Q rba
```

### CMD command
``` shell
cd: - directory, go to
```

### List command
``` shell
dir: - list files
```

### Delete folder and commit command
``` shell
cd your-repository
git rm -r folder-name
git commit -m "Remove folder-name"
git push origin main
```


# Git Commands

## To Clone online Github projects
``` shell
git clone https://github.com/google/rba
mkdir my-new-thing
cd my-new-thing
git init
```

### Mac copy code: rba is the folder name
``` shell
cp -r ../rba/* ../rba/.github .
```
### Windows copy code: rba is the folder name
``` shell
xcopy /E /I ..\rba\* .
```
### Commit changes after modify the codes: test with -a or without -a, should do the samething
``` shell
git add *
git commit -a -m 'Applying RBA Code'
git commit -m 'Applying RBA Code'
```




### push local project to GitHub:
``` shell
git remote add origin [URL of your GitHub repository]
git add .
git commit -m "Initial commit"
git push -u origin main
```

### List all the branches in your local repository. The branch you are currently on will be highlighted and marked with an asterisk (*)
``` shell
git branch
git push origin master (or main)
git push --set-upstream origin master (or main)
```

# Pull changes from online
``` shell
git pull origin main --(or master)
```
