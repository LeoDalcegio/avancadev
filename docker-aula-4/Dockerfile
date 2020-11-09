FROM golang:1.15

WORKDIR /go/src/leodalcegio

COPY . .

RUN GOOS=linux go build

EXPOSE 9091

ENTRYPOINT [ "./leodalcegio" ]