FROM alpine
RUN apk add --update --no-cache curl py-pip wget busybox-extras netcat-openbsd python bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
