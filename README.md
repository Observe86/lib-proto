# lib-proto

Shared Protobuf/gRPC schemas.

## Getting Started

Download protoc for your machine from here: https://github.com/protocolbuffers/protobuf/releases

## Generate Go structs and gRPC interfaces

```bash
go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.36.6
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.3.0
```

```bash
make proto-gen-go
```
