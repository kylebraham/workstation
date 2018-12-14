FROM fedora:29
WORKDIR /root

RUN dnf update --refresh -y && \
    dnf install git flatpak ansible -y
CMD "bash"