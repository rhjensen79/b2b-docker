#tags 14.04 16.04 18.04 20.04 20.10 21.04 latest=20.04 rolling=20.10 devel=21.04
FROM ubuntu:20.04
LABEL maintainer="jensenr@vmware.com"
WORKDIR /tmp
COPY . .
EXPOSE 80/tcp
ENV autoug=rocks
RUN apt update && apt -y install python

ENTRYPOINT /tmp/start.sh
