添加新用户和新用户组

添加新用户：

sudo adduser 新用户名

依次输入信息确认命名

查看用户：

/home目录下，多出新用户的宿主目录

可以在图形界面使用新用户登录

在/etc/passwd文档的末尾处，新增新用户相关信息（用户uid，用户组gid，宿主目录，默认解析器）

在/etc/group文档的末尾处，新增新用户相关信息



删除用户

sudo deluser 用户名

who查看正在使用的用户

sudu -9 -u pkill 用户名字，关闭用户的所有进程

删除完成之后，

vi /etc/group和

vi /etc/passwd里面的对应该用户的信息相应随之删除

/home 目录下，新用户的宿主目录，不会被系统自主删除，可以使用sudo rm -rf



扩展

添加用户组，sudo addgroup 组名

删除用户组，sudo delgroup 组名

