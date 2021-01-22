#tags 14.04 16.04 18.04 20.04 20.10 21.04
FROM ubuntu
LABEL maintainer="jensenr@vmware.com"
WORKDIR /tmp
COPY . /tmp
EXPOSE 80/tcp
ENV autoug=rocks
RUN apt update && apt -y install python

CMD ./start.sh
