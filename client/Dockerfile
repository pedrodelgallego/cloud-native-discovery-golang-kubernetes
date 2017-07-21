FROM alpine

EXPOSE 8080

copy client /app/client
RUN chmod +x /app/client

ENTRYPOINT /app/client
