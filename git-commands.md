To check the git version -> `git --version`

To check the git cofig --> `git config --list`

To edit the username and email -> `git config --global user.name "Mahesh Kumar"`
`git config --global user.email "maheshcodeinn@gmail.com"`

To exit out of the command prompt editor -> enter `:q`

To initilize git in root folder -> `git init`

To display .git folder -> Go to settings (cmd + ,) -> search for files.exclude -> remmove existing .git

To know more about the changes in repository -> `git status`

To ignore files and folders -> create `.gitignore` file and mention files and folders there.

To add changed files in the staging area -> `git add .` or `git add file_name`

To bring back files from staging are to untracked area -> `git reset .`

To commit the changes (snapshot) -> `git commit -m "initial commit"`

shorthand syntax -> `git commit -a -m "initial commit"` or `git commit -am "initial commit"`

To open the preview of readme file `cmd+k v`

Differences in file changes can check using VSCode git diff

Git Lens is popular extension for VSCode Editor

To check remote repos -> `git remote` or `git remote -v`
To add remote repo to git repo -> `git remote add origin https://github.com/gmkcodeinn/git-fundamentals.git`
To know more about remote repo -> `git remote show origin`

To push the code -> `git push origin master -u` -> mentioning as upstrem branch (as single source of truth)
