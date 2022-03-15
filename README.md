- 'git init' : Intitalize current folder as git repositry
- 'git clone <URL>': brings git repo from url to current folder
- 'git status' : Tells us what we need to know about our repository
- 'git add <FILE>' : add <FILE> to the satging area

- 'git commit' : opens text editor to write commit message
  - 'git commit -m "MESSAGE" ' : Writes message as a commit without a text editor

- 'git log' : Shows log(history) of our commits
  - 'git log --oneline' : shows shorter onelone commit

- 'git diff' : compares current uncommited satate to last known git state
  - 'git diff --staged' : runs git diff btw staging area and last known state
  - 'git dif HEAD~<NUMBER>' : compares head with commit <NUMBER> ago (relative)
  - 'git diff <HASH>' : compares head with the commit in hash

- ' .gitkeep ' : create this file in empty folder to keep track of empty folders
- ' .gitignore ' : this file contsains the list of the files that should be ignored by git
