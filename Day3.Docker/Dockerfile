FROM alpine:latest
LABEL maintainer="Konstantin Bobokov"
LABEL description="Day 3 docker practice"
RUN apk add --no-cache bash && \
apk add --update python3 && \
rm -rf /var/cahce/apk/*
ADD README /usr/share/info/
ENTRYPOINT ["bash"]
