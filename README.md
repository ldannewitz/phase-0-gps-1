# phase-0-gps-1

git clone https://github.com/ldannewitz/phase-0-gps-1.git
--clone remote repo to local repo
ls
--list directories
cd phase-0-gps-1/
--change directory to local repo
touch awesome_page.md
--create new file
git add awesome_page.md
--stage changes for commit
git status
--checking status of staged files
git commit -m "Add awesome page file"
--commit changes
--commit messages = present tense, capitalized first letter, under 50 letters

git push origin master
--push local changes to remote repo from master branch

git checkout -b add-command-log
--create new branch & also moving to it
ls
--list directories
open README.md
-- open README file in sublime
history | tail -20
--check command history