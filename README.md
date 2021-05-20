# go-dev-env
General development and test environment for Go.  
You should customize this repository to your ones.

# Usage
For the first time to build or apply the changes, run the following codes.  
```
$ cd go-dev-env
$ docker-compose up -d --build
```

**NOTE: Assume that your $GOPATH is set to `$GOPATH:$HOME/go`! If not so, change the `go-dev-env/docker-compose.yml` accordingly**

After building or running, to enter the shell, run code written below.  
```
$ docker exec -it goapp_goapp_1 sh  
```
