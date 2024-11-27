this is so I do not have to switch between cd and mkdir again and again
---
# install 
download it form github
```
git clone https://github.com/U2kn0wn/Smart_Directory
```
then run the install.sh file
```
chmod +x install.sh``
./install.sh
```
and you are done installing it


# Use
to use it type

```
. sd <directory name>
```
if the direcotry exists in you current working directory it will cnage your directroy to that, if not it will ask you 
```
the directory does not exist do you want to create one
```
press `y` and it will create you one press any other button and it will terminate
if you wish to go back a directory type 
```
. sd ..
```
if you wnat to go your /home/$user directory (or your home directory) type
```
. sd
```
