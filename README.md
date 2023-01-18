# ddd
When cloning, use SSH. Let me know if you run into any problems getting this to work.
After cloning the repo locally, this process will help keep your repo relatively clean.

1. `git fetch`
    *Update your repo with references to changes made by others*
2. `git pull`
    *Merge changes gathered from **git fetch** with changes not in your local repo*
3. Modify code or add new code
4. `git add` _filepath_ or `git add .` ("." is all changes in your current directory)
5. `git status` (check what has changed)
6. CONDITIONAL: `git fetch` (check if anything has been added since you last checked)
7. CONDITIONAL: `git pull` (merge changes from repository to local if necessary)
8. `git commit -m` "Version comment" *There are standards I'd like to use for version commits as well, but we can get into those later
9. `git push` (Adding `-u` sets it up for tracking the repository online)