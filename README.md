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
```Shell
scp -r -i key.pem localPath remoteUser@host:path.
```

####Open Docker shell in running container
```Shell
docker exec -it ID|Name bash
```

####Build node.js package.json with defaults
```Shell
npm init -y
```

####Copying Nano text blocks
use CTRL+Shift+6 to mark the beginning of your block
move cursor with arrow keys to end of your block, the text will be highlighted.
use CTRL+K to cut/delete block.
To paste the block to another place, move cursor to the position and the use CTRL+U. You can paste the block as often as you want to.

####Size of Dir
```Shell
du -sh
```
