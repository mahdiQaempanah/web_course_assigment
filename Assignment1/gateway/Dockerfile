FROM golang:1.20

WORKDIR /src

COPY . /src/

RUN go mod tidy

EXPOSE 6433

CMD go run main.go