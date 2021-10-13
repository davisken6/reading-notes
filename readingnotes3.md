# Git

## What is Git?

**Git** is a distributed version control system **(DVCS)**. **GitHub** :octocat: is a cloud based repository for Git where you can manage your code. A **DVCS** is type of version control where your code that you enter is mirrored onto your fellow developer's computers. This makes working on a group project much smoother.
The way that Git stores your data in a folder each time you commit, or save changes, to your work is by taking a **snapshot**. 📸
There are <ins>3 main states that Git files can live in</ins>. 



**1.Committed**: Data is securely stored in a local database. 



**2.Modified**: File has been changed but not committed to the database. 



**3.Staged**: Flagged a file's changed version to be committed in the next snapshot.


First you must install Git onto your terminal. If you have a MAC, use this [link](http://git-scm.com/download/mac). If you have WINDOWS, use this [link](http://git-scm.com/download/win). For LINUX, use this [link](http://git-scm.com/download/linux).

## Getting Started

Upon installing Git, you will need to make some customizations for your usage. You will first need to set your username and email address to use with ever Git commit.
The command for this is "**git config**". Here is an exmaple of how I set this up on my computer.



git config --global user.name "Kendrah Davis"


git config --global user.email "davisken6@yahoo.com"

Next, let's choose a text editor. We will use Emacs. The command for this is: "git config --global core.editor emacs"

If you need to check your **settings** ⚙️, use the "git config --list" command.

For **help**, use either "git help *command*", "git *command* --help", or "man-git-*command*".

### ACP

In order to sync your code from GitHub onto your computer, we will use something called **ACP** (Add, Commit, Push).

To **add** or clone, use "git add (name of file)"

**You can run "git status" at any point to see where you are in the ACP process.**

To **commit**, run "git commit -m" and insert a commit message of what you did.

Finally, to **push**, run "git push origin main"

