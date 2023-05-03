regenerate:
	go install github.com/hessamalipour/protobuf/protoc-gen-gogo
	protoc --proto_path=.:$(GOPATH)/src/:$(GOPATH)/src/github.com/hessamalipour/protobuf/protobuf/ \
	--gogo_out=. events.proto 
