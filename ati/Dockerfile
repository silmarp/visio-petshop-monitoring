FROM golang:latest

WORKDIR /app

COPY go.mod go.sum main.go build.sh ./

RUN chmod +x build.sh

RUN ./build.sh

EXPOSE 3000

CMD ["app"]
