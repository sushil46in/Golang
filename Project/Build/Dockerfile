FROM golang:alpine
RUN mkdir /app
COPY $(Build.ArtifactStagingDirectory) /app
WORKDIR /app
RUN go build -o main . 
CMD ["/app/main"]