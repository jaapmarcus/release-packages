# release-packages

# apt server

Multiple code names can be supplied  as apt/jammy apt/focal apt/bionic

```
export GPG_TTY=$(tty)
freight-add package-name.deb apt/codename
freight-cache
```

# DNF / Yum
cp pacakge.rpm /var/www/html/folder/
rpm -addsign /var/www/html/folder/*.rpm  

cd /var/www/html/folder/
createrepo .
