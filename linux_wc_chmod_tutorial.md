wc -l file 显示文件的总行数
wc -c file 显示文件的总字节数
wc -w file 显示为文件的总单词数
wc file 显示文件的总数，总字节数，总单词数
wgoami命令：查看当前用户是谁

chmod命令：修改文件权限
-u(user)用户权限
-g(group)同组用户权限
-o(other) 其他人权限
-rwx读写执行权限
添加权限
删除权限
赋予权限
chmod -u +r -g +x -r file
chmod u=rx o=rw file
上面修改权限的方式是文字设定法
还有一种数字设定法
rwx分别对应421
chmod 463 file
ll
-r--rw--wx
r:4
w:2
x:1
每一组权限0~7
