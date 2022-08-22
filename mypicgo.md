## picgo+typora+github

这三个软件配合可以实现你的笔记再github上显示图片，这里主要记录picgo的安装设置

![image-20220822132753073](https://raw.githubusercontent.com/unstoppablezhou/picgo_note/main/img/image-20220822132753073.png)



在github上搜索下载picgo，按指示安装，最好自己选择路径。



打开picgo下选择github设置



注意格式的填写：



设定仓库名是你在github上的仓库名



分支是下面的main，有人master



设定token是在github设置的setting中最下面的developer settings下的personal access tokens,右边new token



取个名，勾选repo就可以点最下面的创建



得到的下面那一串就是token，复制到设定token就行



接下来的指定路径随便写个就好了



最后自定义域名，格式是：https://raw.githubusercontent.com/你自己的github名/仓库名/分支名

https://raw.githubusercontent.com/unstoppablezhou/picgo_note/main



测试上传，点击上传区，拖一张图片进去上传，如果失败，就删除github中的token重新创建，重新复制到picgo，这是我遇到的唯一问题。



最后上传成功，在typora的偏好设置中的图像，选择上传图像，下面就勾选第一个对本地xxx，下面设置你的picgo安装路径，选择picgo(app)



最后大功告成。