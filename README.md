java
====



go and goweb
http://my.oschina.net/astaxie/blog/124040
http://www.yankay.com/go-clear-concurreny/

cellphone game
http://www.58player.com/course.php
http://blog.csdn.net/AC_huang/article/category/2245823/3
http://www.cnblogs.com/zilongshanren/archive/2012/02/17/2356516.htm
http://blog.csdn.net/ku726999/article/details/38121927
http://www.cocoachina.com/cocos/20140120/7724.html
http://www.jikexueyuan.com/course/34.html




swift    http://dev.swiftguide.cn/


git config --global http.proxy http://:@proxy.tencent.com:8080



git config --global http.proxy=proxy.tencent.com:8080

git push https://sunfu103@github.com/sunfu103/php.git

git config --global http.sslcainfo "D:\Program Files (x86)\Git\bin\curl-ca-bundle.crt"

git config --global http.sslCAInfo "D:\Program Files (x86)\Git\bin\curl-ca-bundle.crt"

http://blog.csdn.net/itstarting/article/details/7305384
http://www.cnblogs.com/igrl/archive/2010/09/17/1829358.html
http://www.cnblogs.com/tugenhua0707/p/4050072.html


git config --global http.proxy proxy.tencent.com:8080    在公司的话需要使用这个代理哦


https://wiki.freeswitch.org/wiki/Git_Tips   git代理的设置参考这个网站



如何让本地的仓库和远程的仓库进行同步

Microsoft Windows [版本 6.1.7601]
版权所有 (c) 2009 Microsoft Corporation。保留所有权利。

C:\Users\sunfu>d:

D:\>cd gitHUB

D:\github>cd php

D:\github\php>git init
Initialized empty Git repository in D:/github/php/.git/

D:\github\php>touch test.txt

D:\github\php>git add test.txt

D:\github\php>git commit -m "first commit"
[master (root-commit) cdaa78d] first commit
 Committer: unknown <sunfu@.(none)>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

If the identity used for this commit is wrong, you can fix it with:

    git commit --amend --author='Your Name <you@example.com>'

 0 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.txt

D:\github\php>git config --global user.name "sunfu103"

D:\github\php>git config --global user.email "sunfu103@163.com"

D:\github\php>git commit -m "first commit"
# On branch master
nothing to commit (working directory clean)

D:\github\php>git status
# On branch master
nothing to commit (working directory clean)

D:\github\php>ssh-keygen -t rsa -C "sunfu103@163.com"
Generating public/private rsa key pair.
Enter file in which to save the key (//.ssh/id_rsa): C:/id_rsa
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:/id_rsa.
Your public key has been saved in C:/id_rsa.pub.
The key fingerprint is:
b5:04:b1:dc:10:1e:b2:48:4d:b7:c1:2c:67:fc:9b:ad sunfu103@163.com

D:\github\php>git config --system http.sslcainfo "E:\Development\Git\bin\curl-ca
-bundle.crt"

D:\github\php>git remote add origin https://github.com/sunfu103/php.git

D:\github\php>git push -u origin master
Username:
Password:
Counting objects: 3, done.
Writing objects: 100% (3/3), 203 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sunfu103/php.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

D:\github\php>ls
test  test.txt

D:\github\php>git status
# On branch master
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       test/
nothing added to commit but untracked files present (use "git add" to track)

D:\github\php>git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

D:\github\php>git add test

D:\github\php>git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#       new file:   test/test1.txt
#       new file:   test/test2.txt
#

D:\github\php>git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#       new file:   test/test1.txt
#       new file:   test/test2.txt
#
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       test/temp/

D:\github\php>git add .

D:\github\php>git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#       new file:   test/temp/temp1.txt
#       new file:   test/test1.txt
#       new file:   test/test2.txt
#

D:\github\php>git commit -m "second commit"
[master 3b8f661] second commit
 0 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test/temp/temp1.txt
 create mode 100644 test/test1.txt
 create mode 100644 test/test2.txt

D:\github\php>git status
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#
nothing to commit (working directory clean)

D:\github\php>git log
commit 3b8f6614ad4e5c0ab5afe87643fa72b71d52daf2
Author: sunfu103 <sunfu103@163.com>
Date:   Thu Nov 6 21:28:09 2014 +0800

    second commit

commit cdaa78d4fcd24aea0b9e91c0ea3432acefd217a1
Author: unknown <sunfu@.(none)>
Date:   Thu Nov 6 21:09:05 2014 +0800

    first commit

D:\github\php>git push origin master
Username:
Password:
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 380 bytes, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/sunfu103/php.git
   cdaa78d..3b8f661  master -> master

D:\github\php>







