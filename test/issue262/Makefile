regenerate:
	go install github.com/hessamalipour/protobuf/protoc-min-version
	go install github.com/hessamalipour/protobuf/protoc-gen-gogoslick
	protoc-min-version --version="3.0.0" --proto_path=.:$(GOPATH)/src/:$(GOPATH)/src/github.com/hessamalipour/protobuf/protobuf/ \
	--gogoslick_out=Mgoogle/protobuf/timestamp.proto=github.com/hessamalipour/protobuf/types:. timefail.proto 
