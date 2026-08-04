FROM docker:29.6.2

LABEL govpf.category="utility"
LABEL govpf.fromimage="docker:29.6.2"

ARG EARTHLY_VERSION=v0.8.16

RUN apk add --no-cache git wget \
    && wget -O /usr/local/bin/earthly \
       https://github.com/earthly/earthly/releases/download/${EARTHLY_VERSION}/earthly-linux-amd64 \
    && chmod +x /usr/local/bin/earthly