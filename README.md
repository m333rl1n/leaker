# Leaker
A tool for finding old version of files and backups.
```console
$ cat urls.txt          
https://hackerone.com
https://hackerone.com/login.php
$ cat urls.txt | leaker 
https://hackerone.com/hackerone.7z
https://hackerone.com/hackerone.backup
https://hackerone.com/hackerone.bak
https://hackerone.com/hackerone.bck
https://hackerone.com/hackerone.bz2
https://hackerone.com/hackerone.copy
https://hackerone.com/hackerone.gz
https://hackerone.com/hackerone.old
https://hackerone.com/hackerone.oring
https://hackerone.com/hackerone.rar
https://hackerone.com/hackerone.tar
https://hackerone.com/hackerone.tar.bz2
https://hackerone.com/hackerone.tar.gz
https://hackerone.com/hackerone.tar.lz
https://hackerone.com/hackerone.tar.lzma
https://hackerone.com/hackerone.lzma
https://hackerone.com/hackerone.sav
https://hackerone.com/hackerone.save
https://hackerone.com/hackerone.tgz
https://hackerone.com/hackerone.tmp
https://hackerone.com/hackerone.zip
https://hackerone.com/hackerone.com.7z
https://hackerone.com/hackerone.com.backup
https://hackerone.com/hackerone.com.bak
https://hackerone.com/hackerone.com.bck
https://hackerone.com/hackerone.com.bz2
https://hackerone.com/hackerone.com.copy
https://hackerone.com/hackerone.com.gz
https://hackerone.com/hackerone.com.old
https://hackerone.com/hackerone.com.oring
https://hackerone.com/hackerone.com.rar
https://hackerone.com/hackerone.com.tar
https://hackerone.com/hackerone.com.tar.bz2
https://hackerone.com/hackerone.com.tar.gz
https://hackerone.com/hackerone.com.tar.lz
https://hackerone.com/hackerone.com.tar.lzma
https://hackerone.com/hackerone.com.lzma
https://hackerone.com/hackerone.com.sav
https://hackerone.com/hackerone.com.save
https://hackerone.com/hackerone.com.tgz
https://hackerone.com/hackerone.com.tmp
https://hackerone.com/hackerone.com.zip
https://hackerone.com/login.php~
https://hackerone.com/.login.php.swp
https://hackerone.com/login.php.bak
https://hackerone.com/login.php.old
https://hackerone.com/login.php.bk
https://hackerone.com/login.php.bck
https://hackerone.com/login.php.1
https://hackerone.com/login.php.2
https://hackerone.com/login.php.3
https://hackerone.com/login.php.4
https://hackerone.com/login.php.5
$ cat urls.txt | leaker | httpx
...
```
