# crontab
go crontab

```bash
go mod edit -replace github.com/coreos/bbolt@v1.3.4=go.etcd.io/bbolt@v1.3.4

go mod edit -replace google.golang.org/grpc@v1.29.1=google.golang.org/grpc@v1.26.0

go mod tidy

go mod github.com/coreos/etcd/clientv3

#old mongo driver is failured
go get github.com/mongodb/mongo-go-driver@v0.0.17
```