# python-ngrok
基本上已经完善！并且24*7小时长时间工作，在期间我们多次尝试断网重连、渠道反复注册等，均无任何问题。

采用多线程异步处理，并发性能相当强悍！

# 运行环境
Python 3.1 以上

# 运行方法
直接运行即可.

# 温馨提示
如果有小伙伴不想依赖环境运行，不妨可以试下PyInstaller，把py编译成可执行文件。

## 更新日记 v1.36(2016/08/29)

***

1.添加日记输出模块,调试输出格式化

2.修复本地映射地址无效转向定制的html页面

3.修复关闭上个线程读写,判断描述符是否有效

4.更改发送心跳周期

5.修复断线后重新赋值心跳变量

***

## 更新日记 v1.32(2016/08/13)

***

1.修复关闭上个线程读写,某些极端情况出错

2.修复组包/拆包在其他版本字节流长度不一致

***

## 更新日记 v1.31(2016/08/11)

***

1.修复本地转发完后,关闭上个线程读写

***

## 更新日记 v1.3(2016/08/10)

***

1.修复可写事件,某些极端情况发送数据出错

2.修复处于被注册的期间,断网导致发送心跳出错

***

## 更新日记 v1.2(2016/08/10)

***

1.转多线程异步处理,大幅提升即时并发性能

2.修复主线程cpu占用过高

3.修复堵塞和非堵塞发送

4.修复读写I/O判断

5.修复输出日记排序

6.优化断线重连机制

7.修复断线后变量无法赋值

8.修复本地转发完后导致远程挂起

9.添加本地映射地址无效转向定制的html页面

***
