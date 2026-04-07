根目录下的子目录

1./bin：用来存放二进制的可执行文件。date、Is、cat、echo...

2./dev:用来存放硬件设备所对应的文件。鼠标、键盘...

在Linux中所见皆文件。

测试命令 sudo cat/etc/input/mice  要求输入密码

3./etc:用来存放系统中的”配置“文件

4，/home:用来存放系统中“用户”宿主目录（家目录）的

对于tarena用户而言，家目录是根目录里home里的tarena

cd的使用：

cd 绝对路径：

绝对路经，从根目录/开始的路径都是绝对路径

举例：cd /bin 或 cd /home/tarena

cd 相对路径

上一级目录：..”

举例：当前在/home目录中，输入cd ..就返回到根目录/中

当前目录：“.”

举例：在/home目录中，我可以输入 tarena进入家目录，我也可以输入./tarena进入家目录

cd 回车

回到家目录

cd -:

回到上一次工作目录

pwd:print working directory缩写，打印当前的工作目录

终端提示符格式：

tarena@tarena:\~$--格式为:用户名@主机名：shell 工作路径 $

$:代表当前用户为“普通用户”。

\#：代表当前用户为“root用户”（管理员）---使用命令sudo su---输入密码然后就切换成root用户了

root@tarena-virtual-machine:/home/tarena#

exit：退出管理员



5./lib 库文件：存放系统使用的库文件

查看标准c库

如果想cd一个文件中包含的某个名字比较长的文件，cd 敲出文件名的前几个字然后tab直接自动填充



6。/root：系统管理员的家目录

7./lost+found 丢失加找回

8./media：插入u盘自动分配到的文件

9./mnt：mount命令手动挂载外部磁盘分配到的文件

10./opt:安装第三方应用程序所放到的目录

11./proc：内存进程文件



../bin/前面的斜杠是目录分隔符，后面的是目录提示符，后者可以省略  



12./tmp：系统提供给用户使用，在程序运行中，需要保存的临时文件存储的位置

就比如我在写hello,c时，需要一个文件载体进行读写，这些文件都存到tmp中



13./usr：unix soft resource：存储用户相关的数据资源

14./var:varable：存放系统在工作过程中经常发生变化的数据资源。如：日志、数据库。





