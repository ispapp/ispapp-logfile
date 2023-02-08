# Running the program

```
export GO111MODULE=off
go get github.com/gorilla/websocket

git clone https://github.com/ispapp/ispapp-logfile
cd ispapp-logfile
```

Run this command with your ISPApp domain and session key.

```
# write to screen
GO111MODULE=off go run ispapp-logfile.go -domain "dev.ispapp.co" -sessionKey "yourhostkey"

# write to /var/log/ispapp-instance-log.log
GO111MODULE=off go run ispapp-logfile.go -domain "dev.ispapp.co" -sessionKey "yourhostkey" > /var/log/ispapp-instance-log.log
```

# license

The project ispapp-logfile is licensed per the MIT License
