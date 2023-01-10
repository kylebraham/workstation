FROM fedora
COPY .. /home/$HOST_USER/ansible


# RUN groupadd -g $HOST_GROUP $HOST_USER  && \
#     useradd --badname --system --create-home --no-log-init -g $HOST_GROUP -u $HOST_ID $HOST_USER  && \
RUN dnf update --refresh -y && \
    dnf install git ansible flatpak -y

# USER $HOST_USER
WORKDIR /ansible
CMD "bash"