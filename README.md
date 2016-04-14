# Linux work

这个库含有我在学习Linux时所写的源代码，共含有四个文件夹  
分别为:  
**Client & Server**  
**Copy**  
**FIFO & pipe**  
**Shell**  

###Client & Server
用户与服务器的通信程序，模拟QQ的群聊功能，使用时请**先启动Server，再启动Client**
  
###Copy  
模仿系统中的cp命令所写的自定义cp程序，编译运行即可
  
###FIFO & pipe  
学习IPC阶段所写的代码，编译运行即可，可以实现父子进程的通信
  
###Shell
学习Shell编程时所写的代码，直接运行即可.程序需要三个参数，第一个参数为一个IP的最后一位(1-254)，第二个参数同第一个参数，第三个参数为一个文件夹的名字.程序的功能是轮流ping某一段的主机，如果能够ping通则将第三个参数(文件夹)压缩后传送过去