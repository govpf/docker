FROM docker:29-git

ARG EARTHLY_VERSION=v0.8.16

RUN wget -O /usr/local/bin/earthly \
    https://github.com/earthly/earthly/releases/download/${EARTHLY_VERSION}/earthly-linux-amd64 \
    && chmod +x /usr/local/bin/earthly