# pkg
apt w no root
# install
```
echo 'PATH=~/.pkg/:$PATH' >> ~/.bashrc &&\
git clone https://github.com/eshnd/pkg ~/.pkg &&\
source ~/.bashrc
```
# usage
`~/.pkg/pkg setup` - each time you connect to webshell (it doesn't auto execute .bashrc usually)
`pkg <package-name>` to install things
