# test-Git

Would this be uploaded?

First, when I type "git add" :
NOTHING happens.

way to solve:
I tried to type /git push/.
Then , a new window jumps out , telling me to Log in by using CODE.


Remember to Connect your Github user before you can really "git push".


/////git commit -m "little"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

新增資料之後: 
////git add .
////git commit -m "try" ( "try"可以任意更改)
[main 4c35049] try
 1 file changed, 11 insertions(+), 1 deletion(-)
////git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Ingrid0501/test-Git.git
   5732a93..4c35049  main -> main


   D:\00_PYTHON_LAB\juillet24\test-Git>git add .

D:\00_PYTHON_LAB\juillet24\test-Git>git commit -m "pikachu"
[main 76cdf51] pikachu
 1 file changed, 28 insertions(+), 1 deletion(-)

D:\00_PYTHON_LAB\juillet24\test-Git>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 925 bytes | 925.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Ingrid0501/test-Git.git
   4c35049..76cdf51  main -> main