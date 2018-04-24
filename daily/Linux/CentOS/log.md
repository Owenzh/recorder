## CentOS Operation info

* 运行脚本
    > CD到脚本所在目录

    > chmod  u+x 脚本名

    > > x  --- execute 
    
    > > u -- user ,文件拥有者.
    
    > >注释：给这个文件加 可执行权限 ，因为默认 vi 写的一个文件 只是 读和写的权限 ，没有 x ,即执行的权限 
    
    > ./ 文件名

* 查看进程
    > ps -ef

* 杀死进程
    > kill -9 pid

* 退出当前用户
    > exit

* 打印文件
    > cat [带路径的]文件
* 修改当前用户的PATH
    > export PATH=/xxx/xx:$PATH

* 查看PATH
    > echo $PATH

* 立刻重启(root用户使用)
    > shutdown -r now

* 查看端口号
  > netstat -ntlp
