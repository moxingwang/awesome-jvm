# jitwatch
- 依赖
    - jvm参数设置：-XX:+UnlockDiagnosticVMOptions -XX:+TraceClassLoading -XX:+LogCompilation -XX:LogFile=C:\service\jitwatch\sandbox\sandbox.log -XX:+PrintAssembly -XX:-BackgroundCompilation
    - hsdis（Hotspot disassemble) 
        - win10 
         - [下载地址](https://www.cnblogs.com/niceboat/p/9786905.html)
         - 使用：保存到jdk目录下\jre\bin\server就可以了


# HSDB(Hotspot Debugger)
- 使用
    jdk目录下（如C:\Program Files (x86)\Java\jdk1.8.0_221\lib）执行java -cp sa-jdi.jar sun.jvm.hotspot.HSDB启动界面

# 字节码idea插件
- ASM Bytecode Outline
- jclasslib Bytecode viewer
