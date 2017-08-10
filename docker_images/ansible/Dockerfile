FROM williamyeh/ansible:ubuntu16.04

COPY docker_keypair /root/.ssh

RUN chmod go-rwx ~/.ssh \
    && echo "\n\nHost *\n\tStrictHostKeyChecking=no\n" >> ~/.ssh/config
