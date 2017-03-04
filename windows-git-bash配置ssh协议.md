#生成RSA密钥对
ssh-Keygen -t rsa -C "your email"

cd ~
cd .ssh
ls
可以看到：id_rsa 、id_rsa.pub(公钥)
cat id_rsa.pub
显示公钥的内容

#在Github网站添加公钥

#使用SSH协议

#...