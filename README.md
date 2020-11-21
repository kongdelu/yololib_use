# yololib_use
### 目的
让 Mach-O 加载我们自己的 framework
### 使用方法
1. 将 yololib 下载下来复制到 usr/local/bin 中 , 这样环境变量就可以在任意路径下使用 yololib；
2. 找一个 Mach-O 文件；
3. 执行命令：yololib mach-o名称 你的framework
4. 修改完毕后就可以利用 MachOView 来看下我们的加载指令添加进去了没，就在 Load Commands段中的 LC_LOAD_DYLIB(你的framework)；
