# 常用命令

---



* 很多人可能在电视我电影中看到类似的场景，
* Linux刚出世的时没有什么图形界面
* 近几年来，尽管Linux发展的非常迅速
* Linux 提供了大量的 

## 1.命令使用方法

Linux 命令格式 :



```
command [-options] [parameter1] ...
```

说明：

* command:命令名，相应功能的英文单词或者单词的缩写\[-options\]: 选项，可用来对命令进行控制，可以 省略， \[\]代表可选 parameter1 ... :产地给命令的参数： 可以是零个一个或多个



例如：

## 2.查看帮助文档

### &lt;1&gt; --help 

一般是linux命令自带的帮助信息

如: `ls --help` 



### &lt;2&gt; man\(有问题找男人，manual\)

man 是linux 提供的一个手册，包含了绝大部分的命令、函数使用说明

该手册分成很多首章节（section）, 使用man时可以指定不同的章节来浏览。



例如： man ls ; man 2 printf

man 中各个section 意义如下：

1. Standard commands \(标准命令\)
2. System calls\(系统调用，如open,write\)
3. Library functions \(库函数，如printf,fopen\)
4. Special devices \(设备文件的说明, /dev 下各种设备\)
5. File formats \(文件格式, 如passwd\)
6. Games and toys \(游戏和娱乐\)
7. Miscellaneous \(杂项、惯例与协定等，例如Linux档案系统、网络协定、ASSCII码；environ全局变量\)
8. Administrative Commands \(管理员命令, 如ifconfig\)

man 是按照手册的章节号的顺序进行搜索的。

man设置了如下的功能键：

| 功能键|功能| 
|-|-|
| 空格|现实手册| 



