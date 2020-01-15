# 开发板开发环境

开发板 A311D 需要安装对应的编译环境，
1. 系统为ubuntu 18.04 64bit 系统
2.需安安装samba 服务，保证window 可以方案linux 共享文件夹，编译代码传递
3. 安装git 工具
4. 安装repo 工具
5. 对应的工具链
GCC Version & Java Version 对应的编译工具链可以通过官网下载：http://releases.linaro.org/archive/13.11/components/toolchain/binaries/
```
gcc-linaro-aarch64-linux-gnu-4.9-2014.09_linux
gcc-linaro-arm-linux-gnueabihf
gcc-linaro-aarch64-none-elf-4.8-2013.11_linux
gcc-linaro-arm-none-eabi-4.8-2013.11_linux
Java version：
openjdk 1.8
```