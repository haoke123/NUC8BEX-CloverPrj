# NUC8BEX-CloverPrj
NUC8BEX Clover EFI project from jianshu

简单安装步骤：

1.用Etcher将镜像写入U盘（需要右键管理员运行）。

2.重启进入BIOS（开机按F2），关闭安全启动。按F10 或者ESC保存重启

3.按F10 选择U盘启动，开头带有UEFI标示的。

4.进入Clover 选择U盘上的安装分区启动。

5.进入安装，分配磁盘，建议固态选择APFS，机械选择HFS+，磁盘名建议起个特别一点的如Mackintosh，Hackintosh等。安装过程会重启若干次，如果出现了新的启动项，就选新的启动。（其实删除EmuVariableUefi-64.efi重启项是可以自动选择的。但是考虑到后面有需要激活iMessage等的同学还是留下了）。
