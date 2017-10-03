FROM ray-xyz.com:9090/ubuntu1604

MAINTAINER Raywang
#
# RUN cd /home/ray/go_workspace/src/wholepro/module/prototest/grpc/client
#
# RUN go build

# RUN cp client ~/workspace/docker/hiapi

ADD bin/client /usr/local/bin

ENTRYPOINT /usr/local/bin/client