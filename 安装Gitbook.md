1.  安装 [Node.js](https://nodejs.org/)
2.  通过 npm 来安装 gitbook

    ```
    npm install gitbook-cli -g
    ```

### 基本使用

1.  `gitbook init` 初始化书籍目录

    > `README.md` 和 `SUMMARY.md` 是两个必须文件, `README.md` 是对书籍的简单介绍, `SUMMARY.md` 是书籍的目录结构

2.  `gitbook serve` 编译和预览书籍

    > 注: `gitbook serve` 命令实际上会首先调用 `gitbook build` 编译书籍，完成以后会打开一个 web 服务器，监听在本地的 4000 端口

打开 http://localhost:4000  即可访问
