FROM ray-xyz.com:9090/ubuntu1604

MAINTAINER Raywang

RUN mkdir -p /shendu/etc

ADD /config /shendu/etc

ADD bin/server /usr/local/bin

ENTRYPOINT /usr/local/bin/server