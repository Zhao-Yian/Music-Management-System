# Music-Management-System
这是一个音乐管理系统，需要配置Apache服务器并连接MySQL数据库

Apache可以到官网下载并安装;

此网站使用后端使用PHP编写，完成与数据库的交互工作;

数据库文件在music文件夹中，其内容爬取自网易云网站，数据库名为music,四张数据表,共计一百万余条记录;

运行Web服务器之后，可以浏览器使用本机域名打开login.html进入登录界面，在文件login.js和login.php中之后可以自行设置登录的用户名和密码，初始的用户名与密码都为:123;

![image](https://user-images.githubusercontent.com/77494834/131940476-d7b5922a-c75f-4379-9cae-0a577cfa6a5e.png)


登录成功之后就可以进行增删改查以及播放音乐等各种操作;

网站提供了歌手界面，点击每位歌手的姓名可以进入该名歌手的歌单界面并播放其歌曲;

![image](https://user-images.githubusercontent.com/77494834/131940510-a43fd24b-6008-4ac7-9ac6-54e9a0caef91.png)


网站还提供了热歌榜和每日推荐歌单界面，由于数据库的数据已经固定，每日推荐无法进行更新，但是我会尽量在每个月更新数据文件;

![image](https://user-images.githubusercontent.com/77494834/131940537-002a9f0a-46c4-42ce-9d0b-9fcb93e72428.png)


网站功能较简单，欢迎大佬继续完善;
