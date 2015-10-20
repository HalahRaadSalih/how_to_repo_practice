# Git Cheatsheet

### Start a new project

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "comment"
```

### Do some work and then save it

First, do some work!

```shell
$ git status
$ git add <whatever file>
$ git status
$ git commit -m "describe your changes"
```

### Share my work

First, create a github repo

```shell
$ git remote add origin git@github.com:<github username>/<name of repository>.git
$ git push -u origin master
```
