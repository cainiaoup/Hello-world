# Hello-world
This is my first repository in the github 



# include“msp430g2553.h”
viod main{
string a[];
a="hello world";
  printf{"%d",a};
}

## update:2020/1/23 
### 1.本次目的是练习本地建仓并且远程提交

### 2.用到的网站教程 
* [markdown教程](https://www.jianshu.com/p/8c1b2b39deb0)(用于github文本记录)
* [github在windows上的配置](https://blog.csdn.net/jal517486222/article/details/79967632)(链接仓库，git使用)

### 3.流程
#### [1]注册github 安装git for windows 
* 注册我原来就有号 安装下载默认即可
#### [2]链接本地仓库和远端仓库
1.在git上建仓并clone上仓库的url(网页链接)
2.在本地选一个自己存工程的文件夹，打开gitbash,输入```git clone url```(将仓库下载到本地)
3.在bash中键入自己的邮箱和用户名 ```git config --global user.email 你的邮箱```  ``` git config --global user.name 你的注册名```
4.然后在仓库的这个文件夹中添加一个test.txt的文件，然后空白处右击，点击Git Bash Here，进入命令窗口，使用如下三条命令即可管理仓库的项目
+ ```git add test.txt```  将本地文件压入暂存区
+ ```git commit -m"你想说的话（可以是中文）"``` 将暂存区文件压入本地仓库区
+ ```git push origin master``` 将文件提交到云端仓库的主支了（也可指定分支）
就此就可以在github的仓库中看到我们提交的文件
###### ps:此处想添加一张图片，但图片所在的文件夹应该放在项目中，but我不知道如何添加一个文件夹，而且我还没有添加ssh key,，我想知道为什么我要添加它！
