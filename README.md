# Kendryte Demo 软件包

这个软件包仅配合 Kendryte SDK 而简单移植的 demo 软件包，可以在 RT-Thread 下简单的选择对应的 demo ，然后通过在 msh 命令行下
执行

```
    msh /> exec_demo
```

来简单的执行对应的demo。

请注意，这个仅是 demo 的软件包，所以仅仅是让 demo 的代码跑起来。因为 demo 代码编写的缘故，基本上运行 demo 后，命令行就会
卡死在 demo 循环中。仅用于评估、使用demo。如果需要做更多的功能，需要对demo代码按照RT-Thread的方式进行更改。
