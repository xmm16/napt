# napt
apt with no root
# install
```
git clone https://github.com/xmm16/napt ~/.napt &&\
chmod +x ~/.napt/* &&\
~/.napt/napt __rcsetup &&\
source ~/.naptrc
```
# usage
`source ~/.naptrc` everytime you connect to webshell
`naptload` if you want to load your packages from your last connection
`napt <package-name>` to install a package and its dependencies
`napt <package-name> upgrade` to upgrade a package and its dependencies
`naptupd` to update and save your package list (run right after installing any package)
`naptrm <package-name>` remove a package
