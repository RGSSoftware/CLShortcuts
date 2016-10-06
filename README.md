# CLShortcuts

###Find the open connection
```Shell
lsof -i -P | grep -i "listen"
```

###Find the open connection by PORT
```Shell
netstat -anp tcp | grep 3000
```

###Kill by process ID
```Shell
kill -9 'PID'
```


