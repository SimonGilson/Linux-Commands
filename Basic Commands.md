### Listing Directory
```
ls - List items in current directory 
ls -al - list all items including hidden items and permissions
```
#### Printing working directory 
```
pwd 
```

### switch user
```
su
```

### Run a command in elevated priveledges
```
sudo
```
### Copying items
```
cp {item location to copy} {location for item to be copied to}
```  
  
### Find file path of file name
```
locate
```

### Locate an item that is a text file type and the name of the file
```
Grep -f txt item.txt 
```

### Make directory in the current directory - permissions will be applied depending on the one used to create the directory.
```
mkdir  
rmdir - Remove directory that has not files in it.  
rm - Remove a directory with files in it.  
```

###  Change directory 
```
cd  
cd .. - go back a directory level
```
### Display all network interfaces
```
ifconfig
```
### Netcat. Use to open a listener on the device. 
```
nc
```
### View a file in nano or start a blank file
```
nano
```
###  Display document in terminal
```
cat
```
### Show connection between this computer and another.
```
ping IP
```
### Make a http request to a website 
```
curl https://URL
```
### Download content from URL
```
wget {url} - 
```

### To create a file with this name
```
touch [filename]
```
### Usueful fo adding text to a file example 
```
echo - echo Hello World >> test.txt will add the text to the file.
```
### Change permissions on a file. Example chmod +x example.py will make the .py executable.
```
chmod +x filename
```
### Displays the name of the machine that the terminal is on.
```
hostname 
```

### Use to install packages. Example sudo apt-get pip will download the packages needed for pip.
```
apt-get 
```
### Show the manual for a tool. 
```
[tool name] man
```

### Download the url in a txt file.
```
wget http://url -O url.txt -o /dev/null
wget http://url - when viewing raw code from github will download the code in it own file.

```

### Put File
```
scp /tmp/file user@x.x.x.x.:/tmp/file
```
### Get File
```
scp user@<remoteip>:/tmp/file /tmp/file
```

### Deleting directory 
```
rm -rf <dir>
```

### List connected drives
```
sudo fdisk -l
```

# Linux System Info

### Get hostname for IP
```
nbstat -A <ip> 
```
### Current Username
```
id
```
### logged on users
```
w
```
### User Information
```
who -a 
```
### Last users logged on
```
last -a 
```
### Process listing {top}
```
ps -ef
```
### Disk Usuage
```
df -h
```
### Kernel Version/ CPU info
```
unanme -a
```

