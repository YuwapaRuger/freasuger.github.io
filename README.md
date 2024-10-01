# freasuger.github.io
theme: jekyll-theme-minimal
title: Octocat's homepage
description: Bookmark this to keep an eye on my project updates!
cd PARENT-FOLDER
$ git init REPOSITORY-NAME
> Initialized empty Git repository in /REPOSITORY-NAME/.git/
# Creates a new folder on your computer, initialized as a Git repository
$ cd REPOSITORY-NAME
# Changes the working directory
$ mkdir docs
# Creates a new folder called docs
$ cd docs
$ git checkout --orphan gh-pages
# Creates a new branch, with no history or contents, called gh-pages, and switches to the gh-pages branch
$ git rm -rf .
# Removes the contents from your default branch from the working directory
$ jekyll new --skip-bundle .
# Creates a Jekyll site in the current directory
