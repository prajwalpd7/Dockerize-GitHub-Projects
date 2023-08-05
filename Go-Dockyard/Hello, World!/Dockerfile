FROM golang:1.20.7-alpine3.18

WORKDIR /app

COPY . .

RUN go build -o hello-world-app .

CMD ["./hello-world-app"]
