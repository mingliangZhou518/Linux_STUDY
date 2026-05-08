修改文所有者和所属组

修改所有者

sudo chown 用户名 文件名

把文件改到该用户旗下

例子:sudo chown zhaoliu file1

file1就所属zhaoliu了

修改所属组

sudo chgrp 用户组名 文件名

一次性修改用户人和用户组

sudo chown 新用户名：新用户组名 文件名

sudo chown zhaoliu:itcast file1

linux是统一化数字管理

你给用户组和用户的命名只是给数字键值id赋值对应的value而已



