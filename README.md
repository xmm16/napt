# pkg
apt with no root
# install
```
git clone https://github.com/xmm16/pkg ~/.pkg &&\
chmod +x ~/.pkg/* &&\
~/.pkg/pkg __rcsetup &&\
source ~/.pkgrc
```
# usage
`source ~/.pkgrc` everytime you connect to webshell
`pkgload` if you want to load your packages from your last connection
`pkg <package-name>` to install a package and its dependencies
`pkg <package-name> upgrade` to upgrade a package and its dependencies
`pkgupd` to update and save your package list (run right after installing any package)
`pkgrm <package-name>` remove a package
