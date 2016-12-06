```
$ su -
$ yum -y remove git

$ cd /tmp
$ wget https://www.kernel.org/pub/software/scm/git/git-2.9.3.tar.gz
 
# 解凍
$ tar -zxf git-2.9.3.tar.gz
 
 
# インストール
$ cd git-2.9.3
$ make prefix=/usr/local all
$ make prefix=/usr/local install
# バージョン確認
$ git --version
git version 2.9.3
```
