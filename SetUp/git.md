Last login: Thu Sep 17 16:17:58 on ttys000
D607-13:~ newschool$ cd Documents
D607-13:Documents newschool$ cd DaleMacDonald/programming/
D607-13:programming newschool$ ls
Python2		README.md
D607-13:programming newschool$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	Python2/

nothing added to commit but untracked files present (use "git add" to track)
D607-13:programming newschool$ git add Python2
D607-13:programming newschool$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   Python2/.ipynb_checkpoints/Untitled-checkpoint.ipynb
	new file:   Python2/Untitled.ipynb

D607-13:programming newschool$ git commit

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'newschool@D607-13.(none)')
D607-13:programming newschool$ git config --global user.email "macdonad@newschool.edu"
D607-13:programming newschool$ git config --global user.name "Dale MacDonald"
D607-13:programming newschool$ git commit
****************** vi happens here *********************
[master 7d02f4f] first construct
 2 files changed, 114 insertions(+)
 create mode 100644 Python2/.ipynb_checkpoints/Untitled-checkpoint.ipynb
 create mode 100644 Python2/Untitled.ipynb

D607-13:programming newschool$ git push --repo https://github.com/mrdale1958/media_practices_programming
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': mrdale1958
Password for 'https://mrdale1958@github.com': 
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 966 bytes | 0 bytes/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/mrdale1958/media_practices_programming
   ac9edc0..7d02f4f  master -> master
D607-13:programming newschool$ 

