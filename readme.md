
# 1. Create or clone project

## to initialize git (only once)
git init

## clone git repo to local pc (only once to create local project)
git clone https://github.com/marishua/sql_learning.git

# 2. Main git commands

## show git current status
git status

## add all untracked files to git repo
git add .

## commit files (or changes) to repo (new log record will be created)
git commit -m 'this is commit comments'

## show git changes log
git log

## reverse made changes (not committed)
git checkout <file_name>

# 3. Sync local project with remote git repo

## send changes to git repo (remote)
git push

## get changes from git repo
git pull
