# 以前写的 C / Linux 代码

这个仓库原来只有一个文件服务器练习，名字就叫 `project`。后来翻 GitHub，发现 2021 年学 C 和 Linux 时建了不少小仓库，找一份代码要来回点好几次。我索性把能直接阅读的代码和笔记按原来的仓库名收到了 [learning](./learning) 里。

扫雷、井字棋、`fork`、`pthread`、`epoll`……当年的写法现在未必还会这么写，但我没为了整理去改动原程序。

| 目录 | 以前练的内容 |
| --- | --- |
| [C](./learning/C) | C 基础题、扫雷、井字棋 |
| [IO](./learning/IO) | 标准 I/O、文件 I/O |
| [Process](./learning/Process) | 进程管理、信号和 IPC |
| [Thread](./learning/Thread) | pthread、互斥锁和信号量 |
| [make-lib](./learning/make-lib) | 静态库、共享库 |
| [Socket](./learning/Socket) | TCP、UDP、I/O 多路复用等 |
| [SQLite3](./learning/SQLite3) | SQLite3 的 C API |
| [Learn-Git](./learning/Learn-Git) | Git 操作练习，含旧分支和标签的文件快照 |
| [1_file_server](./1_file_server) | 文件服务器实验（原来就在这里） |

这份仓库适合翻旧代码，不适合直接拿去上线。尤其是文件服务器，输入处理、路径检查和访问控制都还有问题。

### 旧仓库的事

我希望以后只在这里查这些练习代码。原来的八个仓库暂时没删除，因为迁入的是代码文件，不是完整 Git 历史。部分二进制产物和 `SQLite3` 的 `my.db` 也还没备份到这里。等这些旧内容妥善备份，再删原仓库比较稳妥。
