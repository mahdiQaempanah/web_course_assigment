FROM golang:1.20

WORKDIR /src

COPY . /src/

RUN go mod tidy

EXPOSE 5052

CMD go run main.go