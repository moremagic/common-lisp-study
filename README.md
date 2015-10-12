# common-lisp-study

「人工知能プログラミングのための Common Lisp 入門」  
http://peatix.com/event/115092  
　　
上記セミナーに参加するためのための学習用環境を作成するためのDockerfileです  
主催者による解説ページ通りの環境を作成しています  　
  
http://blog.livedoor.jp/s-koide/archives/2287418.html  
  Ubuntu15.04,   
　sbcl, sb-aclrepl, quicklisp  
  
## quick start
$ git clone https://github.com/moremagic/common-lisp-study.git  
$ cd common-lisp-study  
$ docker build -t common-lisp-study .  
  
$ docker run -d -p 22:22 common-lisp-sutdy  
$ ssh root@localhost  
root@localhost's password: root  
