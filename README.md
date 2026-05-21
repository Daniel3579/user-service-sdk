```
cd user-service-sdk
protoc -I ./proto --go_out=. --go-grpc_out=. ./proto/*.proto
```