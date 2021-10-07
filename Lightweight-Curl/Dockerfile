FROM alpine:3.14.2 AS builder

RUN apk update && apk add curl

FROM busybox:1.33.1

COPY --from=builder /lib /lib
COPY --from=builder /usr/lib /usr/lib
COPY --from=builder /usr/bin /usr/bin

CMD [ "/bin/sh" ]
