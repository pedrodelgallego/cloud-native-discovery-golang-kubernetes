FROM alpine

EXPOSE 8080

COPY simple-k8s-server /app/simple-k8s-server
RUN chmod +x /app/simple-k8s-server

ENTRYPOINT /app/simple-k8s-server
