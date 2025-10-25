# django1

## First Steps:

```sh
cd codeSync
mkdir luis
cd luis
mkdir django1
cd django1
# Created a  git repo inside ~/codeSync/luis/django1
git init
git config --global user.name maldocode
git config --global user.email luisarturo102011.gmail.com
git config --global push.default matching 
git config --global credential.helper store 
git config --global core.editor code
git config --global core.autocrlf false 
git config --global init.defaultBranch master
git config --global core.symlinks true
touch README.md
code README.md # I add this ext to this file
git status
git add .
git commit -m "Created my first readme file"
git log

brew install python3
python3 -m pip install Django
python3 -m venv django1

django-admin startproject mypage
cd mypage
python3 manage.py runserver
```
