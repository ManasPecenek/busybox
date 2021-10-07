FROM alpine:3.14.2 AS builder

RUN apk update && apk add curl

FROM busybox:1.33.1

COPY --from=builder /bin/sh /bin/sh
COPY --from=builder /lib /lib
COPY --from=builder /usr /usr

CMD [ "/bin/sh" ]
