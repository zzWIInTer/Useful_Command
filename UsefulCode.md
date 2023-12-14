### Delete, remove directory
rmdir /S /Q rba

### CMD command
cd: - directory, go to

### List command
dir: - list files

# Git Commands

## To Clone online Github projects
``` shell
git clone https://github.com/google/rba
mkdir my-new-thing
cd my-new-thing
git init
```

### Mac copy code:
cp -r ../rba/* ../rba/.github .
### Windows copy code:

xcopy /E /I ..\rba\* .

### Commit changes after modify the codes
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
git push origin master #(or main)
git push --set-upstream origin master #(or main)
```

# Pull changes from online
git pull origin main --(or master)
