你真猛你真帅


使用ssh的方式去链接远程仓库

1.生成本地电脑的 公钥 和私钥
ssh-keygen -t rsa -C "xxx@xxx.com"


1.1 将本地生成的公钥写到远程平台上（github）

2.将本地仓库 与远程仓库建立PY关系

git remote add origin xxx