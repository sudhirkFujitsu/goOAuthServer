simple Oauth2 Server

### Build and run

```bash
go build server.go

./server
```

## open your web browser 
grant token request
http://localhost:9096/token?grant_type=client_credentials&client_id=sudhierk&client_secret=skNew85&scope=read