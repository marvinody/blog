+++
title = "initial commit"
date = 2019-09-10T21:28:15-04:00
author = ""
cover = ""
tags = ["self"]
description = "My adventures in git"
showFullContent = false
+++

`git add .`

`git commit -m 'initial commit'`

`git push origin master`

# git
An extremely powerful tool that can be arcane and mystical to anyone starting out with it.

I am by no means an expert at it (I learned about submodules just making this site), but I've certainly encountered several issues during my time at a bootcamp.

### "I can't make a commit"
So this has a few possible causes.

1. No git repo in the folder because someone downloaded a zip instead of cloning
2. No access to git repo because it was cloned with `sudo git clone`

To fix 1, (make sure it's forked first) and add your remote with `git remote add origin <forked_github_url>` and then `git pull origin master`. Hopefully you have no merge conflicts and you're good to go!

To fix 2, run `ls -la` and look to see what the `.git` folder looks like. If it's owned by root or someone that's not you, change dir to one above and run something like `sudo chown -R $(whoami) <folder>` and then try again.

### "I committed on master when I wanted a new branch"
I thought I learned how to solve this by myself and then realized I picked it up from [ohshitgit](https://ohshitgit.com/) (great read).

`git branch <branch>`

`git reset HEAD~1 --hard`

`git checkout <branch>`


---


I hopefully will come back and add more as we encounter them but I already have a feeling I'll forget.
