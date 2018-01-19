
#### 本文主要阐述以下:
* ---梳理众所周知的短小函数的好处
* ---解释为什么我认为有些好处表现的并不好
* ---解释为什么短小函数是适得其反的
* ---列举我认为短小函数真正有用的场景

人们给出的编程建议似乎都在赞美短小函数的优美和简洁。比如被看做编程圣经的《clean code》一书中，有一章专门用来讲述方法。这一章用一个非常差劲的函数做开篇，这个函数就非常冗长。这一章也把函数过长看做最大的错误。书中写到：
> 这个函数不仅非常长，而且有很多重复代码、使用了很多奇怪的字符串和不常见的数据类型和api。给你三分钟，你能够理解者函数吗？答案也许是否定的。这个函数中实现了太多逻辑，有很多不同层级的抽象。在if控制语句中有太多奇怪的字符串和古怪的函数调用。
这一章探讨了哪些特性能够使代码“易于阅读和理解”、“allow a casual reader to intuit the kind of program they live inside”，在探讨这些之前简化函数也许就能够达到以上目的。

函数应该短小这个观点几乎被认为是不容置疑的。这种论点频繁出现在代码审查、twitter讨论、会议演讲、书籍播客、关于重构的文章中等等各种场景。几天前我在tweeter上看到了这种观点：



----------------

via：https://medium.com/@copyconstruct/small-functions-considered-harmful-91035d316c29

译者：[wkpaochuan](https://github.com/wkupaochuan)

本文由 [GCTT](https://github.com/studygolang/GCTT) 原创编译，[Go 中文网](https://studygolang.com/) 荣誉推出
