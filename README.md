# pkg
apt w no root
# install
```
git clone https://github.com/xmm16/pkg ~/.pkg &&\
chmod +x ~/.pkg/* &&\
touch ~/.pkgrc &&\
echo -e '\nPATH=~/.pkg/:$PATH\nalias pkgupd="source ~/.pkgrc"' >> ~/.pkgrc &&\
source ~/.pkgrc
```
# usage
`source ~/.pkgrc` everytime you connect to webshell
`pkg <package-name>` to install things
`pkgupd` to update your package list (run right after installing any package)
`pkgrm` remove packages 
