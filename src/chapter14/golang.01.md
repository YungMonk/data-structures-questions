#### Golang的汇编过程

在程序编译的时候,汇编的目的是把汇编代码转化为机器指令，因为几乎每一条汇编指令都对应着一条机器指令，所以汇编的过程相对而言非常的简单。
汇编操作所生成的文件叫做目标文件（Object File），目标文件的结构与可执行文件是一致的，它们之间只存在着一些细微的差异。目标文件是无法被执行的，它还需要经过链接这一步操作，目标文件被链接之后才可以产生可执行文件。
