From golang:1.16.4
WORKDIR /app
copy go.mod go.sum ./
RUN go.mod download
COPY..
RUN go build -o main 
EXPOSE 7071
CMD ["./main"]