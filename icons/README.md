看着参差不齐的图标真的不爽  
于是我尽可能将图标弄成统一的圆形，基于Marea，但是改掉了几个应用的图标（因为太难看）  
解压放到/usr/share/icons，然后在菜单栏中设置即可

### 问题解决
问题1：我安装gitkraken并将程序放到dock中发现图标小了一圈  
解决：
使用文本编辑器将/usr/share/applications/gitkraken.desktop中icon=app改成Icon=app改成Icon=gitkraken，不然默认使用的图标会是/usr/share/pixmaps/app.png而不是我们主题中的svg文件
