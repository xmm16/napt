# pkg
apt w no root
# install
```
git clone https://github.com/xmm16/pkg ~/.pkg &&\
touch ~/.pkgrc &&\
echo -e '\nPATH=~/.pkg/:$PATH\nalias pkgupd="source ~/.pkgrc"' >> ~/.pkgrc &&\
source ~/.pkgrc
```
# usage
`pkg <package-name>` to install things
