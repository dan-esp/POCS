FROM golang:latest

WORKDIR /app

COPY . .

RUN go get
RUN go build -o app/bin .
 
ENTRYPOINT [ "./app/bin" ]
