
FROM golang:1.20
WORKDIR /app
COPY . .
RUN go build -o main main.go
EXPOSE 8001
CMD ["./main"]
