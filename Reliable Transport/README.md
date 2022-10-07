## Terminal
First compile the binary.
```
make
```
Then open two terminals:

terminal 1
```
$ ./reliable 6667 -w 5 -d localhost:6666
```
terminal 2
```
$ ./reliable 6666 -w 5 -d localhost:6667
```
check ports etc.
```
$ sudo netstat -upa | grep reliable
```
