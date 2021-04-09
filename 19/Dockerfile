FROM docker:19.03.5-git
ARG EARTHLY_VERSION=v0.5.9
RUN wget https://github.com/earthly/earthly/releases/download/${EARTHLY_VERSION}/earthly-linux-amd64 -O /usr/local/bin/earthly \
        && chmod +x /usr/local/bin/earthly
