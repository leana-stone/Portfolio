# UX Portfolio

## Git Commands for regular work

**To "save" your changes**
```
git add .
git commit -M "put a note here about what the changes are for future reference - try to be as factual and specific as you can be."

```

**To push your changes up to github**
```
git push origin master
```

**If you see this message:**
```
To github.com:leana-stone/Portfolio.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'git@github.com:leana-stone/Portfolio.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```
**It means someone else (like erica) made changes since you last worked on the project. When that happens, first add and commit your changes:**

```
git add .
git commit -M "put a note here about what the changes are for future reference - try to be as factual and specific as you can be."
```

**Then do this:**
```
git pull origin master
```

**A page will open that says:**

```
Merge branch 'master' of github.com:leana-stone/Portfolio

# Please enter a commit message to explain why this merge is necessary,
# especially if it merges an updated upstream into a topic branch.
#
# Lines starting with '#' will be ignored, and an empty message aborts
# the commit.
```

**Add a quick note after the first line, save and close the file**

**Then you'll be able to push your changes up with this:**

```
git push origin master
```

-------------------


## Things I need to remember to get my project started

* item
* item
* item





## Things I need to remember to get my project updated/saved on Github

* item
* item
* item



## Other Things I need to remember about my project

* item
* item
* item
