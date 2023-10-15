# myapp/app/Dockerfile
FROM golang:1.21

WORKDIR /app

COPY . .

RUN go build -o myapp

CMD ["/app/myapp"]

