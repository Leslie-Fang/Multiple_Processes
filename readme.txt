首先在linux下安装cmake 最好3.6.3版本，最新版本也可以

1.新建一个文件夹 以code为名字为例
2.将hwk4文件夹移入code文件夹中
3.进入code文件夹，命令行输入   cmake  hwk4
4.命令行输入 make，之后会生成一个叫main的可执行文件
5.测试， ./main (进程数量） 下限 上限 > result.txt
  例子：./main 10 300000 300100 > result.txt
6.在我的电脑上大概要运行5-10分钟，然后在code的文件夹下面会产生一个叫result.txt的文件，记录了程序运行的结果
