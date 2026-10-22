# 以前写的 C / Linux 代码

这个仓库原来只放了一个文件服务器练习，名字就叫 `project`。后来翻 GitHub，发现 2021 年学 C 和 Linux 时建了不少小仓库，找一份代码要来回点好几次。我索性把它们按原来的仓库名收进了 [learning](./learning) 目录。

我没有趁这次整理去重写那些代码。扫雷、井字棋、`fork`、`pthread`、`epoll`，有些地方现在回头看肯定还能改，但原稿留着才看得出当时是怎么练的。

| 目录 | 里面放了什么 |
| --- | --- |
| [C](./learning/C) | C 基础题、扫雷、井字棋 |
| [IO](./learning/IO) | 标准 I/O、文件 I/O |
| [Process](./learning/Process) | 进程管理、信号与进程间通信 |
| [Thread](./learning/Thread) | pthread、互斥锁和信号量 |
| [make-lib](./learning/make-lib) | GCC 静态库与共享库 |
| [Socket](./learning/Socket) | TCP、UDP、并发服务端、I/O 多路复用 |
| [SQLite3](./learning/SQLite3) | SQLite3 的 C API |
| [Learn-Git](./learning/Learn-Git) | 以前练 Git 用的占位文件 |
| [1_file_server](./1_file_server) | 我当时做的文件服务器练习（原本就在这里） |

### 关于这些旧代码

这是学习存档，不是现成的项目合集。网络程序尤其别直接放公网跑：文件服务器的输入处理、路径拼接和访问控制都还需要重新做。

为了方便集中翻阅，我把其他仓库的**文件复制**了过来，原仓库没有删，原来的提交记录也没有迁移到这里。想看当时的提交过程，可以去原仓库：[C](https://github.com/Coniper/C) · [IO](https://github.com/Coniper/IO) · [Process](https://github.com/Coniper/Process) · [Thread](https://github.com/Coniper/Thread) · [make-lib](https://github.com/Coniper/make-lib) · [Socket](https://github.com/Coniper/Socket) · [SQLite3](https://github.com/Coniper/SQLite3) · [Learn-Git](https://github.com/Coniper/Learn-Git)。

我没有把旧的可执行文件和示例数据库再复制一遍；原 `1_file_server` 目录里的构建产物暂时仍按原样保留。
