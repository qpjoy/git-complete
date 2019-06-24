# Complete Guid for Git



## resources
1. https://hipsum.co/
2. http://www.initializr.com/
3. https://github.com/scm-ninja/starter-web


```
git verson
git config --global user.name "Abe Lincoln"
git config --global user.email "mrabe@git.training"
git config --global --list

git clone https://github.com/qpjoy/git-complete

git status
git add
git commit
git commit -am ""


git push origin master

git ls-files

git reset HEAD file

git checkout -- file

git mv file file1

mv file file1
git add -A

git add file1
git add -u

git rm file
git checkout -- file

rm file
git add -A


git help log
git log --abbrev-commit
git log --oneline --graph --decorate
git log loguuid...loguuid2
git log --since="3 days ago"
git log -- file
git log --follow -- file
git show loguuid
git log --all --graph --decorate --oneline
git config --global alias.hist "log --all --graph --decorate --oneline


.gitignore

git commit -am ""
git pull origin master
git push origin master


git config --global --list
git config --global -e


git difftool
git difftool HEAD
git diff --staged HEAD
git difftool --staged HEAD
git difftool -- file


git log

git diff commituuid HEAD
git diff HEAD HEAD^
git diff commituuid1 commituuid2
git diff master origin/master


git branch -a
git branch mynewbranch
git checkout mynewbranch
git log --oneline --decorate
git branch -m mynewbranch newbranch
git branch -d newbranch
git checkout -b newbranch


git merge newbranch
git merge newbranch --no-ff
git merge newbranch -m ""


git rebase master
git add
git rebase --continue
git rebase --abort


git fetch
git pull -rebase origin master


git stash
git stash apply
git stash list
git stash drop

git stash -u

git stash pop

git stash save "simple chages"
git stash drop stash@{1}
git stash clear

git stash branch newchanges


git tag myTag
git tag --list
git show myTag
git tag --delete myTag

git tag -a v-1.0
git tag -a v-1.1
git commit --amend
git tag v-1.2 -m "Relase 1.2"

git diff v-1.0 v-1.2
git difftool v-1.0 v-1.2

git tag -a v-0.9-beta commituuid -m "Beta release 0.9"
git tag -a v-0.8-alpha commituuid -m "Alpha release 0.8"

git tag -a v-0.8-alpha -f commituuid

git push origin tagname
git push origin master --tags
git push origin :tagname

git reset HEAD^1
git reset HEAD@{2}
git reset HEAD^^

git branch -D test

git reflog
```