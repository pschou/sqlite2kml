PROG_NAME := "geo-sqlite-dumper"
VERSION = 0.1.$(shell date +%Y%m%d.%H%M)
FLAGS := "-s -w -X main.version=${VERSION}"


build:
	GOOS=linux go build -ldflags=${FLAGS} -o ../${PROG_NAME} .
