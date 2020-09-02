# basic-go-http

#### Run the application
```cmd
$ go run ./basic_http_example.go

```

#### How to resolve error like 
```txt
2016/07/19 03:51:11 listen tcp :8080: bind: address already in use exit
   status 1

Run command below to kill services using port 8080
$ ps -aux | grep 'go run'
```
