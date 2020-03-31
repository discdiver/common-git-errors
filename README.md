# Common Git Errors and Solutions

I see new users to git with the same solution.


### Problem: You made a git repository inside a git repository on your computer
### Short-term fix: 
### Long-term solution: 
When you want to initialize or clone down a git repository, make sure you aren't in a git repository by running `git status`.
---
### Problem: You are stuck in VIM because you didn't include a full commit message or have a merge conflict.
### Short-term fix: Press `esc` (the escape key). Then type `:` (colon). Then type `q`. 🎉

### Long-term solution: 
Always add a commit message and avoid merge conflicts. You can set up a default text editor for git. If you have [VSCode]() (and it's free and I recommend it), see [this link]() to learn how you can set it up as your default for git.
---

### Problem: I want to reset my local git repository to match a repository in the cloud (for example, on GitHub). Warning, this will wipe out any local changes.

### Short-term fix: `git reset hard --head`

### Long-term solution: 
---
### Problem: I have a merge conflict so I can't pull down an updated repository.
### Short-term fix: `git reset hard --head`
### Long-term solution: 
---
### Problem: I forked and cloned a repository but can't pull down changes from the upstream repository.
### Fix: set the upstream repository. See how to do that [here]() 

---
### Problem: I hate git
### Short-term fix: deep breaths, smile, go for a walk.
### Long-term solution: learn more git. 😀



