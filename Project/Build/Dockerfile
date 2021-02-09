FROM golang:alpine
RUN mkdir /app
COPY $(Pipeline.Workspace)/app /app
WORKDIR /app
RUN go build -o main . 
CMD ["/app/main"]