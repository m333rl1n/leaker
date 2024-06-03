# Leaker
A tool for finding old version of files and backups.

### Usage:
1. clone repo:
```bash
git clone https://github.com/m333rl1n/leaker.git
cd leaker
```
2. give it a single URL:
```bash
./leaker https://domain.tld/config.php

# result:
https://domain.tld/index.php~
https://domain.tld/.index.php.swp
https://domain.tld/index.php.bak
https://domain.tld/index.php.old
https://domain.tld/index.php.bk
https://domain.tld/index.php.bck
https://domain.tld/index.php.1
https://domain.tld/index.php.2
https://domain.tld/index.php.3
https://domain.tld/index.php.4
https://domain.tld/index.php.5
```
2. Or pipe a list of URLs:
```bash
cat urls.txt | ./leaker

# result:
https://domain.tld/index.php~
...
https://domain.tld/index.php.2
https://domain.tld/index.php.3
https://domain.tld/index.php.4
....
https://www.sub.domain.tld/domain.save
...
https://www.sub.domain.tld/domain.tld.bak
...
https://www.sub.domain.tld/sub.7z
...
https://www.sub.domain.tld/sub.gz
...
```
