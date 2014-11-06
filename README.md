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

D:\github\php>






