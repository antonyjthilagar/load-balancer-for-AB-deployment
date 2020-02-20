FROM golang:1.12-alpine
WORKDIR /go/bin/
COPY ./golang-webserver .
RUN chmod a+x /go/bin/golang-webserver
EXPOSE 8080
ENTRYPOINT ["/go/bin/golang-webserver"]
