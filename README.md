# coding

making some Changes ex1.py

to see what changes locally:  git status

On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	ex1.py

to add new or modified file
gzcc:coding chloe$ git add ex1.py


then commit the changes use:

gzcc:coding chloe$ git commit -m"initial save"
[master a63152d] initial save
 1 file changed, 3 insertions(+)
 create mode 100755 ex1.py

Then upload to the internet repo use:


gzcc:coding chloe$ git push
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 330 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/chloe56/coding.git
   7de8d4f..a63152d  master -> master
gzcc:coding chloe$
