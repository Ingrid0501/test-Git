# test-Git

##test for git pull

edit time: 30 juillet 2023

#如果想要格行，需要打上"  "(two spaces)。

Would this be uploaded?

𓃠𓃠𓃠🐳🐳🌌🌌🐳 初始問題 🐳🐳𓆝𓆝𓆝🐳🐳🐳🌌🌌🐳🐳

First, when I type "git add ." :  
NOTHING happens.  


🐳🐳way to solve:
I tried to type /git push/.  
Then , a new window jumps out , telling me to Log in by using CODE.  

Remember to Connect your Github user before you can really "git push".    


/////git commit -m "little"  
On branch main  
Your branch is up to date with 'origin/main'.  

(沒有新增任何改變可能是因為前面跳過了 git add .)  
Changes not staged for commit:  
  (use "git add <file>..." to update what will be committed)  
  (use "git restore <file>..." to discard changes in working directory)  
        modified:   README.md  

no changes added to commit (use "git add" and/or "git commit -a")        

𓃠𓃠𓃠𓃠🐳🐳🐳🌌🐳 更新上傳程式碼:  範例 1 🐳𓆝𓆝𓆝🐳🐳🐳🐳

////git add .

////git commit -m "try" ( 名字"try"可以任意更改)  
[main *******] try
 1 file changed, 11 insertions(+), 1 deletion(-)    

////git push  
Enumerating objects: 5, done.  
Counting objects: 100% (5/5), done.  
Delta compression using up to 12 threads  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/Ingrid0501/test-Git.git  
   5732a93..*******  main -> main      

𓆝𓆝🐳 範例 2 🐳🌌𓆝𓆝
////git add .  

////git commit -m "pikachu"  
[main *******] pikachu
 1 file changed, 28 insertions(+), 1 deletion(-)  

////git push  
Enumerating objects: 5, done.  
Counting objects: 100% (5/5), done.  
Delta compression using up to 12 threads  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (3/3), 925 bytes | 925.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/Ingrid0501/test-Git.git  
<<<<<<< HEAD
   4c35049..76cdf51  main -> main      




  ......🐳🐳𓃠𓃠🐳複製其他人的程式碼/專案(repo):  範例 1🐳🐳🐳........

////git clone https://github.com/jimmg35/smoking.git    
  
Cloning into 'smoking'...  
remote: Enumerating objects: 31, done.  
remote: Counting objects: 100% (31/31), done.  
remote: Compressing objects: 100% (21/21), done.  
Receiving objects:  64% (20/31)used 29 (delta 10), pack-reused 0  
Receiving objects: 100% (31/31), 2.02 MiB | 5.38 MiB/s, done.  
Resolving deltas: 100% (12/12), done.  


=======
   4c35049..76cdf51  main -> main  
>>>>>>> 3fa7d48e7185839e707964709437a8f41dbb7569
