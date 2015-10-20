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

### Help someone else with their code

Find the code on github that you want to contribute to and fork it.

```shell
$ git clone git@github.com:<your username>/<name of repository>.git
```

Then make some changes that you think are important

```shell
$ git add <your file>
$ git commit -m "A really thorough explanation since this is someone else's work"
$ git push origin master
```
Finish what you started working on, then push up any additional commits

File a pull request with the commits in it that you want to share. Make sure you have a good explanation in the pull request of what it is, what it's intended to do, and some nice language.

### How to work on two different things at the same time

Branching is when you want to work on two things at the same time that might span over multiple commits but you want to keep them seperate

