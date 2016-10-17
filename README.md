# CLShortcuts

####Find the open connection
```Shell
lsof -i -P | grep -i "listen"
```

####Find the open connection by PORT
```Shell
netstat -anp tcp | grep 3000
```

####Kill by process ID
```Shell
kill -9 'PID'
```

####Shutdown MongoDB
```Shell
$ mongo
use admin
db.shutdownServer()
```

####Start Ngrok, only HTTPS, with PORT 
```Shell
ngrok http -bind-tls=true 'PORT'
```

####Start and Stop Nginx Mac
```Shell
//Start
sudo nginx

//Stop
sudo nginx -s stop
```

####Copy files from local host to remote host
scp -r -i key.pem localPath remoteUser@host:path.
