# test-Git

##test for git pull

edit time: 24/ 30 juillet 2023

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



<30 juillet 2023>
  ......🐳🐳𓃠𓃠🐳複製其他人的程式碼/專案(repo):  範例 1 🐳🐳🐳........

////git clone https://github.com/jimmg35/smoking.git    
  
Cloning into 'smoking'...  
remote: Enumerating objects: 31, done.  
remote: Counting objects: 100% (31/31), done.  
remote: Compressing objects: 100% (21/21), done.  
Receiving objects:  64% (20/31)used 29 (delta 10), pack-reused 0  
Receiving objects: 100% (31/31), 2.02 MiB | 5.38 MiB/s, done.  
Resolving deltas: 100% (12/12), done.  

........🐳🐳𓃠𓃠🐳git clone 複製他人檔案到自己電腦的資料夾之後，能不能夠update呢? ( 例如學長更新程式碼 ...) ......


#@因為我改不了學長的，所以以下改由我自己的檔案。  
1.自己在github編輯( 加上##test for git pull )  
2.接著 要用 git pull


////git pull    
remote: Enumerating objects: 5, done.  
remote: Counting objects: 100% (5/5), done.  
remote: Compressing objects: 100% (2/2), done.  
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0  
Unpacking objects: 100% (3/3), 698 bytes | 1024 bytes/s, done.  
From https://github.com/Ingrid0501/test-Git  
   fbb676f..3fa7d48  main       -> origin/main  
error: Your local changes to the following files would be overwritten by merge:  
        README.md  
Please commit your changes or stash them before you merge. 🐳🐳建議我commit一個檔或用暫存檔🐳🐳 
Aborting    
Updating fbb676f..3fa7d48    

....問題: 似乎是我在本地的檔案有修改，卻在git pull之前沒有上傳到github更新，所以失敗。

....解決: 本地檔案 git add . ==> git commit -m "uniqueName" ==> 這裡不能 git push上傳，否則  


>>>git add .

>>>git commit -m "dimache"
[main 21562f0] dimache
 1 file changed, 22 insertions(+), 5 deletions(-)  


(BAN)!!!!>>>git push  絕對不能在此就push

To https://github.com/Ingrid0501/test-Git.git  
 ! [rejected]        main -> main (non-fast-forward)  
error: failed to push some refs to 'https://github.com/Ingrid0501/test-Git.git'  
hint: Updates were rejected because the tip of your current branch is behind  
hint: its remote counterpart. Integrate the remote changes (e.g.  
hint: 'git pull ...') before pushing again.  
hint: See the 'Note about fast-forwards' in 'git push --help' for details  


在回到更新的步驟>>>git pull   
Already up to date.    

Enumerating objects: 10, done.  
Counting objects: 100% (10/10), done.  
Delta compression using up to 12 threads  
Compressing objects: 100% (4/4), done.  
Writing objects: 100% (6/6), 972 bytes | 972.00 KiB/s, done.  
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0  
remote: Resolving deltas: 100% (2/2), completed with 1 local object.  
To https://github.com/Ingrid0501/test-Git.git  
   3fa7d48..fe13dab  main -> main  

這時候你就可以看到 GITHUB 的檔案同步更新到 本地檔案。
