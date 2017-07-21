FROM alpine

EXPOSE 8080

COPY server /app/server
RUN chmod +x /app/server

ENTRYPOINT /app/server
