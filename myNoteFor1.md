```bash
date
```

显示时间

```bash
echo "something"
```

返回内容，可以是文件，如

```bash
echo $PATH
```

这是返回 PATH 变量

```bash
which echo
```

查看环境变量中程序的位置

```bash
pwd
```

"print working directory"，打印工作目录

```bash
cd /home
cd ~
cd -
```

"change directory"，改变工作目录

`~`与`\home`等价

`-`表示上一个目录

```bash
cd .
cd ..
```

"."是指当前目录，".."是指父目录

```bash
ls
ls ..
```

列出当前目录的所有文件，可以在后面加上路径，则会列出路径的所有文件

```bash
ls -l
```

给出文件的具体信息

```bash
mv a.md b.md
```

将 a 文件移动（改名）为 b 文件

```bash
cp a.md b.md
```

复制一个 a 文件命名为 b 文件

```bash
rm /
```

 删除目录

```bash
man rm
```

man 指令给出对应 order 的manual

```bash
< file 
> file #重写
>> file #追加
```

可以分别重定向输入和输出

```bash
cat file
```

打印文件内容

```bash
order1 | order2
```

管道（pipe）将第一个程序的输出作为第二个程序的输入

```bash
sudo order
sudo su #以 root 登陆shell
exit #退出 root 用户
```

do as su(super user)，以 root 用户的身份执行命令

```bash
tee file
```

输出输入流中的内容到输出流和文件中

```bash
open file
```

用合适的软件打开文件
