.DEFAULT_GOAL := build
.PHONY:fmt vet build
fmt:
	go fmt ./...
vet:
	go vet ./...
build: fmt
		go build