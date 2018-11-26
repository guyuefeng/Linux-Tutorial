# MAC 系统安装 JDK 及环境变量设置


## MAC 苹果系统下安装JDK（JDK1.8）并配置系统环境变量

- 到Oracle官网下载JDK 1.8 安装包
 - 此时（20181126）最新版本：`jdk-8u191-macosx-x64.dmg`
 - 官网：<http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html>


- 打开下载好的安装包安装到MAC系统
 - 下载完成后得到 `jdk-8u191-macosx-x64.dmg` 安装包
 - 双击dmg安装包，按照提示完成安装
 
- 配置系统环境变量
 - 上面步骤只是将JDK1.8复制到系统，我们还需要配置环境变量，使得terminal等终端上可以使用JAVA。
 - 查找JDK的真实主目录，如 `/Library/Java/JavaVirtualMachines/jdk1.8.0_191.jdk/Contents/Home`
 - 编辑启动文件 `vim .bash_profile`
 ```
 export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_191.jdk/Contents/Home
 ```
 
- 验证JDK是否安装成功
 - 检查 JDK 命令：`java -version`
 

## 资料

 - <https://blog.csdn.net/deliciousion/article/details/78046007>
 - <>
 - <>
 - <>
 