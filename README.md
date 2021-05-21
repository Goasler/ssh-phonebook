# ssh-phonebook
Store your often used ssh destinations and select them from a nice shell menu.

Please consider:
1. This is my first Linux bash script that i ever uploaded to github. 
2. I assume that there are already similar programs. But this one is self coded by me and if this Program helps you at your daily work routine or is in any other way useful for you, feel free to use it.
3. There is no option to save passwords, while saving passwords in configuration files is unsecure and strongly not recommended!
 
 
## Install
I read often that you should not interrupt your OS while putting files in any binary folders like /bin, /usr/bin, etc. 
 
Based on that, i recommend you to install it on your home directory and add this directory to $PATH.
```
cd ~/
mkdir .bin 
cd .bin
(copy/download the two files in that folder)
chmod +x ssh-phonebook
echo 'export PATH="$HOME/.bin:$PATH"' >> ~/.bashrc 
```
 
## Usage
```
ssh-phonebook
```


If you miss any features feel free to open a feature request.
