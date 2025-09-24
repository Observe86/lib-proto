# lib-proto

Shared Protobuf/gRPC schemas.

## Getting Started

Download protoc for your machine from here: https://github.com/protocolbuffers/protobuf/releases

## Generate Go structs and gRPC interfaces

```bash
protoc -I=proto \
    --go_out=./gen --go_opt=paths=source_relative \
    --go-grpc_out=./gen --go-grpc_opt=paths=source_relative \
    proto/*.proto
```
