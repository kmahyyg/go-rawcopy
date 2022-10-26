# go-rawcopy

RawCopy - Golang implementation

# Dependencies

```bash
go get -u golang.org/x/sys/windows
go get -u www.velocidex.com/golang/go-ntfs
```

# Build and Run

```bash
go build -o go-rawcopy.exe -ldflags='-s -w' -trimpath ./main.go
```

# License 

GNU AGPL v3.0

## Library License

- https://github.com/velocidex/go-ntfs Apache-2.0

Thanks to: https://github.com/velocidex/velociraptor (GNU AGPL v3.0)