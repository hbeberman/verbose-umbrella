FROM hebebermhostcr.azurecr.io/base:v1

RUN tdnf makecache && \
tdnf update -y && \
tdnf install -y rpm icu ca-certificates

ENTRYPOINT ["/usr/bin/echo", "hello world"]
