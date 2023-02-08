# 1. 
#### *Configuring git*

This changes the name associated with this git configuration

**`git config --global user.email "Tony-Pichai" `**

This changes the email.

Leave out `--global` to do one time instances of naming.




# 2. 
cd to where you want to make your repository

**`git innit`** 




# 3. Begin Staging

**`git status`** - Tells you what's going on, is it a repository yet?

**`git add filename.ext`** - Adds file to the `staging Environment`

or

**`git add .`**  - Short hand, adds files

**`git status`** - Has it been staged? (green when yes)

**`git log --oneline`** - Show's you what's committed and your branch




### 3b.
Other options for adding files

**`git add -a`**
*or* **`git add --all`** - sends all the files

At this point you might go into VIM

1. `i` - This puts you into insert mode
2. Type your comment
3. `Esc` - Puts you into escape mode
4. `:wq` - To exits vim
   * `:` - Puts you in command mode
   * `w` - stands for write
   * `q` - quit
   



# 4. Commit

Happy with the work? commit the file to repository.

`git commit -m "Include a message"`

*Git Commit* takes a snapshot of your staging area, you also get a hash code assigned to this snapshot.

`git status` - check if it worked

`cmd+shit+.` To reveal hidden files - objects folder shows the history

## 4 b.

If this doesn't work you can skip the **staging environment** bit and automatically stage everything with `-a` (all)

`git commit -a -m "first commit"`
* `-m` stands for message


[How to visualise this](https://www.youtube.com/watch?v=UYtUFKn1hXw)



# 5. - New files?

Updated the files on your computer?

1. Add updated files the staging area first.
2. git add .

Want to scrap something  staged?

1.` git reset HEAD --howToGit.MD`
2. This will un-stage that particular file





# 6. Branching out

1. To create a branch

**`git branch "branch-name"`**

2. Display *all* of your branches

**`git branch -a`**

You will see "* master" in green if that's the branch you're on

3. To switch to another branch

**`git checkout branch-name`**

4. Check it again

**`git branch -a`**





# 11. Merge

switch to your main branch
- **`git merge branch-name`**

Enter the branch you want to merge with it
- **`git merge branch-name`**

This will merge and add additional files 





# 12. GitHub
Method 1, push code to a github repo

1. make a repo on github 
2. **`git status`** check git status is clear
3. Push your files to which branch
4. **`git push https://github.com/TonyPichai/howToGit.git master`**
