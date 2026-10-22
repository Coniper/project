# make-lib

当时想弄明白 `gcc` 是怎么把几个源文件变成库的，就做了两套小例子：

- `staticlib/`：先编译出 `.o`，再用 `ar` 打成静态库。
- `sharelib/`：用 `-fPIC` 和 `-shared` 生成共享库。

具体敲过的命令记在 [note.txt](./note.txt)。旧的 `.a`、`.so` 也还在仓库里，换环境最好从源码重编。
