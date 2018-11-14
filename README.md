# coding
gzcc:coding chloe$ vi ex1.py
gzcc:coding chloe$ chmod +x ex1.py
gzcc:coding chloe$ pwd
/Users/chloe/python_study/coding
gzcc:coding chloe$ atom .
gzcc:coding chloe$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	ex1.py

nothing added to commit but untracked files present (use "git add" to track)
gzcc:coding chloe$ git add ex1.py
gzcc:coding chloe$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   ex1.py

gzcc:coding chloe$ git commit -m"initial save"
[master a63152d] initial save
 1 file changed, 3 insertions(+)
 create mode 100755 ex1.py
gzcc:coding chloe$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean
gzcc:coding chloe$ git push
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 330 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/chloe56/coding.git
   7de8d4f..a63152d  master -> master
gzcc:coding chloe$
