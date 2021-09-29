FROM alpine AS builder

RUN apk update && apk add curl

FROM scratch

COPY --from=builder /bin /bin
COPY --from=builder /lib /lib
COPY --from=builder /usr /usr

CMD ["/bin/sh"]
