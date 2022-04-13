pwd : shows where in the system you are
ls : lists the items in the current directory
    can use the flags -a to show hidden files or -l to show more detailed info
cd [filepath] : enters the directory indicated by the filepath
    no listed filepath returns to the root file
mkdir [name] : creates a new directory at the location you are at
touch [name.ext] : creates a new file of the type .ext
mv [a] [b] : relocates item a to location b, can be used to rename a to b
cp [a] [b] : creates a copy of a in location b
open [name] : opens the file in what the system deems the best program 
git init : initialises an empty git repository in current directory
git status : shows what is currently being tracked 
git add [name] : adds an item to git tracking, use '.' for entire directory
git commit : takes a snapshot of the project
    flag -m then use "" to add comment of what the change is
git log : shows a list of commits
git remote push add origin [url] : links to github with the url
git push origin main : uploads the repository to github
git clone [url] : downloads a clone of a git repository
git pull : downloads latest changes from github