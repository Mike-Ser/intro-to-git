---
layout: page
title: Code snippets
permalink: /code/
---

Here is some inline code: `git status`

Exiting vim: `:wq`


Configure git:

`git config --global user.name "Your Name"`

`git config --global user.email "your@email"`


Checking git status:

`git status`


Creating a repository (repo):

`mkdir hello-world`

`cd hello-world`

`git init`


Adding and committing files

`touch index.md`

`git status`

`git add index.md`

`git status`

`vim index.md`

`# Hello, world!`

`:wq`

`git add index.md`

`git commit -m 'Add index.md'`
