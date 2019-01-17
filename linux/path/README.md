# 环境变量
> 拼接PATH用符号" : "  如 <br>
`export PATH=$PATH:/usr/local/nginx/sbin:/usr/local/go/bin:` 

## Golang
```bazaar
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export GO111MODULE=on

export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin
# 下方是个人自定义,方便命令行中调用
export GOPRO=$GOPATH/src/github.com/sun-wenming
```

## nginx
```bazaar
export PATH=$PATH:/usr/local/nginx/sbin
```
