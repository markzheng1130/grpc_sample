# grpc_sample

### [install]
- https://grpc.io/docs/languages/go/quickstart/
- go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28
- go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2

### [run]
- step 1, go run greeter_server/main.go
- step 2, go run greeter_client/main.go

### [re-build proto]
- step 1, cd to "grpc_sample" folder
- step 2, protoc --go_out=. --go-grpc_out=. helloworld/*.proto
