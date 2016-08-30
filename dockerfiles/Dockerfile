#FROM golang:1.6.2
# RUN apt-get update     && apt-get install -y libldap2-dev     && rm -r /var/lib/apt/lists/*
FROM offlineregistry.dataman-inc.com/centos7/base:20160325175751

RUN mkdir -p /go/
ADD ./bin.tar.gz /go/
WORKDIR /go/bin/
ENTRYPOINT ["/go/bin/harbor_ui"]
