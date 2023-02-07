# 1. 

**`git config --global user.name "Tony-Pichai"`**

This changes the name associated with this git configuration

**`git config --global user.email "Tony-Pichai" `**

This changes the email.

Leave out `--global` to do one time instances of naming.

# 2.

cd to where you want to go

**`git status`** - Brings us what's going on

**`git add filename.ext`** - Adds file to the `staging Environment`

**git status** - Check if its ok?

# 3.

**`git add -a`**
*or* **`git add --all`** - sends it

At this point you might go into VIM

1. `i` - This puts you into insert mode
2. Type your comment
3. `Esc` - Puts you into escape mode
4. `:wq` - To exits vim
   * `:` - Puts you in command mode
   * `w` - stands for write
   * `q` - quit
   
# 4.

Once you're happy with your work, commit the file to git.

`git commit -m "It's best practice to include a message"`

If that doesn't work try this:

`git commit -a -m "first commit"`
* `-m` stands for message