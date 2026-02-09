# Git

### Basic commit process
~~~
git commit -m "message"
git add .
git push
~~~

### Visit a past point in history
 - Note: this detaches HEAD
~~~
git checkout <commit-hash>
~~~

### Switch to a branch
 - Note: can be used to return from detached HEAD state (discards any changes)
~~~
git checkout <branch>
~~~

### Create a new branch
 - Note: creation based on the active state (point in history e.g. headless state)
~~~
git checkout -b branch
~~~

### Combine two branches
 - Let <feature> be the branch you want to reduce into <main>
~~~
git checkout <feature>
git rebase <main>
~~~

### Check git history
~~~
git log
~~~