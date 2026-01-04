FROM alpine:3.20
RUN apk add --no-cache bash
WORKDIR /app
COPY run-tests.sh .
RUN chmod +x run-tests.sh
CMD ["sh", "-c", "echo 'Container running'; sleep 3600"]
