# go-package

```bash
git submodule add <git_url> <path>
```

```bash
GIT_TAG="v1.2.0" # change as needed
go get -d -u github.com/golang/protobuf/protoc-gen-go
git -C "$(go env GOPATH)"/src/github.com/golang/protobuf checkout $GIT_TAG
go install github.com/golang/protobuf/protoc-gen-go
```

golang.org/x/net
golang.org/x/tools
google.golang.org/grpc
github.com/golang/protobuf/protoc-gen-go
