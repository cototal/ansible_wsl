Install ansible

```
sudo apt install python3-pip
pip3 install --user ansible
sed -i '1s_^_export PATH=$PATH:~/.local/bin \n_' ~/.bashrc
. ~/.bashrc
```
