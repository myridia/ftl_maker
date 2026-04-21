## Create Debian Package Structure
```
dh_make -i --createorig -e info@myridia.com -c gpl3 -y 
```
## Build the Package
```
dpkg-buildpackage -us -uc -b
```

