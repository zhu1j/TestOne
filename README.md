SSH配置，防止push/pull 出现网络443端口连接超时问题

C:\Users\34129\Desktop\codewoking\课程\Web开发课\考试参考\学生登录管理\frontend>ssh-keygen -t ed25519 -C "zhujiejava1@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\34129/.ssh/id_ed25519): 
Created directory 'C:\\Users\\34129/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again: 
Your identification has been saved in C:\Users\34129/.ssh/id_ed25519
Your public key has been saved in C:\Users\34129/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:BUdcFYV0KvvqoiXWuwmmBHkFQoT5S6tykwK5TeAW2q8 zhujiejava1@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|   =+ . .oo..o++o|
|  o  . . o.   .o |
|   .    . . . .  |
|..  o. . .   o   |
|o+..oo. S   .    |
|+oo oo   .   .   |
|o+ +  . = o   .  |
|+ * .. + +.o .   |
| +Eo  . ..++o    |
+----[SHA256]-----+


在终端输入以下命令，自动复制公钥到剪贴板：  clip < ~/.ssh/id_ed25519.pub