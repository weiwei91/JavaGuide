# java异常体系
# 体系图
![java异常体系图](https://s1.ax1x.com/2020/09/09/w8KBWT.png)

# 解析Java处理机制
- 问题:Error和Exception的区别？
- Error:程序无法处理的系统错误，编译器不做检查
- Exception:程序可以处理的异常，捕获之后可能恢复
- 总结: Error是程序无法处理的错误，Exception是可以处理的异常

# 责任角度理解
1.Error是jvm需要负担的责任       
2:RuntimeException是程序需要负担的责任        
3.Checked Exception可检查异常是Java编译器需要负担的责任     

# 常见Error以及Exception
```
Error
1.NoClassDefFoundError - 找不到定义的异常
2.StackOverflowError - 深递归导致栈被耗尽而抛出的异常
3.OutOfMemoryError - 内存溢出异常
非RuntimeException
1.ClassNotFoundException
2.IOeXCEPTION
RuntimeException
1.NUllPointerException
2.ClassCastException
3.IllegalArgumentException
4.IndexOutBoundsException
5.NumberFormatException
```
