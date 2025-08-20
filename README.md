# Gym-Git-Exercise-Solutions

this repo is for git exercises by the Gym

# Gym-Git-Exercise-Solutions

this repo is for git exercises by the Gym

## Bundle 1

### exercise 1

```bash
Gym Git Exercise Solutions
$ git init

Initialized empty Git repository in C:/Gym Git Exercise Solutions/.git/

Gym Git Exercise Solutions (master)
$ git branch -M main

Gym Git Exercise Solutions (main)
$ git remote add origin https://github.com/jabo-arnold-landry/Gym-Git-Exercise-Solutions.git

Gym Git Exercise Solutions (main)
$ git pull origin main
From https://github.com/jabo-arnold-landry/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD

> git add .
> git commit -m 'first-exercises'
> git checkout -b dev
Switched to a new branch 'dev'
> git checkout -b test
Switched to a new branch 'test'
> git branch -D test
Deleted branch test (was 0b566d1).
```

## Bundle 1

### exercise 2

```bash
> git stash
> git stash pop
> git pop stash@{0}
> git pop stash@{1}
> git pop stash@{2}
> git add .
> git commit -m 'added-home-and-about'
> git reset --hard
```

## Bundle 2

### exercise 1

```bash
> git checkout -b ft/bundle-2
> git commit -m 'added-services-page
> git push origin -u ft/bundle-2
```

## example of PR description

# Task checklist

- [x] made some changes to existing pages
- [x] added services page

## Bundle 2

### exercise 2

> git pull origin
> git checkout -b ft/service-redesign

## Bundle 3

### exercise 1

```bash
git checkout -b ft/team-page
git checkout -b ft/contact-page
git revert 07c8da9c74c395eecf646210c0bae8216f73ea65
git checkout -b  ft/faq-page
git revert 2c8fef0
```
