### \## 10-6  读取文件元数据

应用程序能够通过调用stat 和fstat函数， 检索到关于文件的信息（元数据）。

stat函数一一个文件名作为输入，并填写st_mode,st_size等成员。 web服务器内容会用到。

fstat函数相似，只不过是以文件描述符而不是文件名作为输入。

st_size成员包含了文件的字节数大小。 st_mode成员编码了文件访问许可位和文件类型。
