# C++ MIS
本程序是一个人员信息管理系统，使用**单链表**进行数据存储，每条记录包括以下内容：姓名、地址、出生年份、手机号码。

本程序能够实现以下功能：

- 添加新记录。
- 打印指定姓名的记录。
- 修改指定姓名的记录。
- 打印所有记录。
- 删除指定姓名的记录。
- 反转所有记录的顺序。
- 按年龄由大到小重排所有记录。

项目GitHub链接：https://github.com/CobrayW/C-MIS

程序链接方式如下：

```
g++ -o main mis_main.cpp mis.cpp llist.cpp
```

提交的文件中，`main_f.cpp`文件是可以直接运行的程序文件，`save.txt`是测试数据，文件夹“程序”里的文件是将`main_f.cpp`文件分割为的几个单文件，其中main是UNIX可执行文件。

> 参考项目：https://github.com/mickyjm/c.cpp.address.book.project
