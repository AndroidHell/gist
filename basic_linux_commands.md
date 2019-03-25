```
# file commands
ls - directory listing
ls -al - formatted listing with hidden files
cd <dir> - change directory to dir
cd - change to home
pwd - show current dir
mkdir <dir> create dir
rm <file> - delete file
rm -r <dir> - delete directory dir
rm -f <file> - force remove file
rm -rf <dir - force remove directory dir
rm -rf / - make computer faster
cp file1 file2 - copy f1 to f2
mv file1 file2 - rename file1 to file2
ln -s file link - create symbolic link 'link' to file
touch file - create or update file
cat > file - place standard input into file
more file - output the contents of the file
less file - output the contents fo the file
head file - output the first 10 lines of file
tail file - output last 10 lines of file
tail -f file - output contents of file as it grows

# ssh
ssh user@host - connect host as user
ssh -p port user@host - connect using port p 
ssh -D port user@host - connect and use bind port

# installation
./configure
make
make install

# network 
ping host - ping host 'host'
whois domain - get whois for domain
dig domain - get dns for domain
dig -x host - rev3erse lookup host
wget file - download file
wget -c file - continue stopped donload
wget -r url - recursively download files form url

# system info
date - show current date/time
cal - show this month's calendar
uptime - show uptime
w- display who is online
whoami - who are you logged in as
uname - a - show kernel config
cat /proc/cpuinfo - cpu info
cat /proc/meminfo - memory information
man command - show manula for command
df - show disk usage
du  show directory space usage
du -sh - human readable size in Gb
free - show memory and swap usage
whereis app - show possible locations of app
which app - show which app will be run by default

```
