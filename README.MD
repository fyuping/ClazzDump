#### 使用方法
java -jar "-javaagent:F:\ClazzDump-1.0.jar=-d=D:/tmp/bytecode/exported/;-f2=org/fyp;-r" xx.jar

　　-d: 设置导出文件的输出目录；

　　-f: 设置需要导出的字节码的前缀；

　　-r: 有该参数代表需要进行包目录的创建，否则生成所有文件到一个目录；