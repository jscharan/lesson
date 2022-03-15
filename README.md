#Git Notes by JSC

- `git init` : Intitalize current folder as git repositry
- `git clone <URL>`: brings git repo from url to current folder
- `git status` : Tells us what we need to know about our repository
- `git add <FILE>` : add <FILE> to the satging area

- `git commit` : opens text editor to write commit message

  - `git commit -m "MESSAGE" ` : Writes message as a commit without a text editor

- `git log` : Shows log(history) of our commits

  - `git log --oneline` : shows shorter onelone commit

- `git diff` : compares current uncommited satate to last known git state

  - `git diff --staged` : runs git diff btw staging area and last known state
  - `git dif HEAD~<NUMBER>` : compares head with commit <NUMBER> ago (relative)
  - `git diff <HASH>` : compares head with the commit in hash

- `.gitkeep` : create this file in empty folder to keep track of empty folders
- `.gitignore` : this file contsains the list of the files that should be ignored by git

  ##Remote Topic

- `git remote add <NAME> <URL>` : adds the <URL> as aremote with the name <NAME>
  - <NAME> is by convention called "origin"
- `git remote -v` : loo at all the remotes we have
- `git remote rm <NAME>` removes remote called Name
- `git push <WHERE> <WHAT>` : pushes the <WHAT> branch to <WHERE>

  - ex : git push origin main

- `git pull <WHERE> <WHAT>` : pulls <WHAT> branch from <WHERE>
