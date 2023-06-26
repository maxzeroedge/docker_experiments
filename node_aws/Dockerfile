FROM alpine:latest
RUN apk update
RUN apk add nodejs npm
RUN apk update
RUN apk --no-cache add curl unzip
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" \
    && unzip awscliv2.zip && ./aws/install

