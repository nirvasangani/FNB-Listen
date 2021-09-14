# commands
### 1. server
```sh
gcc server.c -o s -lpthread ./s 127.0.0.1
```

### 2. client
```sh
gcc pkg-config gtk+-2.0 --cflags client.c -o client pkg-config gtk+-2.0 --libs ./client 127.0.0.1
```
# Requirement
- VLC media player 
