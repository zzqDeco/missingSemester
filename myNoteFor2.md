Bash 存在一套 programming 的逻辑

我们可以声明一些变量比如

```bash
foo=bar
```

不过，我们不能在等号前后添加空格，空格作为命令的分隔符，这会让 bash 认为你是想要寻找一个名为 foo 的命令以等号和bar为参数执行操作

在这里，bar被当作字符串处理

在 bash 中，双引号字符串和单引号字符串没有太大的差别，主要体现在，双引号支持转译，而单引号不支持

可以创建 .sh 文件编写脚本函数

```bash
!!
```

可以替换上一行命令

```bash
||
&&
;
```

bash 中的与或有短路机制，可以用于条件执行

分号分割命令，不受影响

![image-20230210164745618](image-20230210164745618.png)

上面是关于`$`的各种用法，详细可以查阅[here](https://tldp.org/LDP/abs/html/special-chars.html)

终端的错误信息通过`STDERR`告知用户: `A value of 0 usually means everything went OK; anything different from 0 means an error occurred.`