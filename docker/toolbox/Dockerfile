FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD uptime && uname
CMD tail -f /dev/null
