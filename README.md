# pkg
apt w no root
# install
```
cp ~/.bashrc .bashrc_old &&\
rm -rf ~/.bashrc &&\
mv .bashrc_old ~/.bashrc &&\
echo 'PATH=~/.pkg/:$PATH' >> ~/.bashrc &&\
git clone https://github.com/xmm16/pkg ~/.pkg &&\
source ~/.bashrc
```
# usage
`~/.pkg/pkg setup` - each time you connect to webshell (it doesn't auto execute .bashrc usually)
`pkg <package-name>` to install things
