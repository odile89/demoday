# Git Demo Day
[git cheat-sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
### Clone
- Create repo in Github online
- Go to folder iterm
- `$ git clone [url]` (find green button clone and download on Github repo)
- Woohoo created your repo locally (your laptop)
- move into this folder:
- `$ cd [folder]` (cd demoday)

### Make changes in repo
- Change file or create/add file 
- Check changes:
- `$ git status` (new changes in red) 
- Prep file for commit
- `$ git add [file name]` 
- Check if everything went oke:
- `$ git status` (from red to green) 
- Doorvoeren van veranderingen (permanent)
- `$ git commit -m "[descriptive message]"` **note: never use !! `$ git commit` !!!**
- Use descriptive message to show what happend to your file (create, edit, change, etc.)

### Push to server
- push all previous commits (changes) to server (in Github.com)
- `$ git push` 

### Pull from server
- `$ git pull`


### Back ground info

#### Git stages: 

c)  Commit staged for commit
    - ready for commit to synchronise the repo on the server
    - push to server to "clear" local master branch  
b)  changes not staged for commit
    - Stage when you made changes in your existing (previously added with `$ git add`) file
    - worked on multiple files? use `$ git commit -a -m "descriptive" `  
a)  untracked 
    - When you create a file for the first time
    - after `$ git status` file is in red in the untracked-stage
    - steps: status, add, status, commit, status, push
    - add multiple files? use `$ git add *.md`  

### Don't forget

- always save your files before adding, committing and pushing 