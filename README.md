# ssh-phonebook
Store your often used ssh destinations and select them from a nice shell menu.

Please consider:
1. This is my first script that i ever uploaded to github. 
2. I assume that there are already similar programs. But this one is self coded by me and if its helps you, feel free to use it.
3. There is no option to save passwords, while saving passwords in configuration files is unsecure and strongly not recommended!
  
  
## Install
```
cd ~/
mkdir .bin 
cd .bin/
(copy/download the files here)
chmod +x ssh-phonebook
echo 'export PATH="$HOME/.bin:$PATH"' >> ~/.bashrc #only needed if you wanna call it from anywhere in your system
```
Install instructions based on https://unix.stackexchange.com/a/51 .

 
## Edit the Config file
```
cd ~/.bin/
nano ssh-phonebook.conf
```
or if you prefer vi
```
cd ~/.bin/
vi ssh-phonebook.conf
```

 
## Usage
```
ssh-phonebook
```
## Disclaimer
These scripts come without warranty of any kind. Use them at your own risk. I assume no liability for any sort of damages using my scripts may cause.
 
  
If you miss any features feel free to open a feature request.
 
If you found any Bugs, let me know and i will fix it as soon as possible.

