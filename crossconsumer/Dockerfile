FROM hebebermhostcr.azurecr.io/base:v1

RUN tdnf makecache && \
tdnf update -y && \
tdnf install -y hello foo

ENTRYPOINT ["/usr/bin/cat", "/etc/hello.txt", "/etc/foo.txt"]
