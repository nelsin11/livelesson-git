- 'git init' : Initialize current folder as a git repository.
- 'git clone <url> : brings the git repo from <url> to current folder
- 'git status: tells us what we need to know about our repository.

- 'git add <file> : adds <file> to the staging area
- 'git commit: open a text editor to write commit message
-  'git commit -m "message" : write message as a commit without a text editor

- 'git log' : shows the log (histroy) of our commits
   -git log --oneline : shows the shorter online commit

- 'git diff' : compare current uncommitted state with last known git state
  - 'git diff --staged : runs git diff between the staging area and last known state
  - 'git diff HEAD~<number> . compares HEAD with commit <number> ago <relative>
 - 'git diff <hash>': compares head with the commit in <hash>
- 'git restore --source <hash or head> <file> : retore file to <hash or head>
- 'git checkout <hash or head> <file> restores file to <hash or head>

  - git checkout <hash or head> if you forget the file you end up in detach
  - git chekcout main : go back to main 
  - git switch main : go back to main

 
 

