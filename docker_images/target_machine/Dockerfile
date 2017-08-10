FROM krlmlr/debian-ssh

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get -y install python \
    && rm -rf /var/lib/apt/lists/*
