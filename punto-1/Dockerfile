FROM alpine:3.20
COPY mensaje.txt /app
RUN apk --no-cache add curl
CMD [ "curl","/app/mensaje.txt" ]