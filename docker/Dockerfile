FROM alpine
RUN apk add --update --no-cache curl py-pip wget busybox-extras netcat-openbsd bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD echo "Hello world from Alpine"
CMD tail -f /dev/null
