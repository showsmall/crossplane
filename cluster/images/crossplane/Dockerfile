FROM BASEIMAGE
RUN apk --no-cache add ca-certificates bash

ADD crossplane /usr/local/bin/
EXPOSE 8080
USER 1001
ENTRYPOINT ["crossplane"]
