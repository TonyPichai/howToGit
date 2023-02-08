# 7 Making branches

>Make a branch and checkout in one-line `git checkout -b branch name`

Or, make a branch like this...

1. cd to to your working dir, create a branch

**`git branch "branch-name"`**

2. Have a look at *all* of your branches

**`git branch -a`**

You will see "* master" in green, that's the branch you're on

3. Switch to your branch

**`git checkout branch-name`**

1. Have a look, where are you

**`git branch -a`**




# 8 Upload your files

Now you're in the branch, create the files you want to work on.

1. Your file status should be untracked, but check anyway

**`git status`**

2. Like normal, add the file to staging area

**`git add .`**

3. Now commit your branch

**`git commit -m "message"`**

# 9
After committing your branched file it's stable and apart from your master

Check it out.
**`git checkout master`**

Go back to the master branch and the file you just created will _**Disappear**_

Go back to your branch

**`git checkout branch-1`**

# 10 Delete
Don't want that branch?

**`git branch -D branch-name`**

For a **_merged_** branch use `-d`