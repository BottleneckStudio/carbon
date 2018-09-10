# Golang Carbon Package.


#### Installation:
```
$ go get -u github.com/BottleneckStudio/carbon
```

#### Usage:
```sh
carbon := carbon.New(time.Now())

timestamp := carbon.CreateFromTimestamp(time.Now().Unix(), "Asia/Singapore")
```

#### For more information, check:
[Carbon Package](https://godoc.org/github.com/BottleneckStudio/carbon)
