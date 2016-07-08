# Initial node.js & npm install using package manager.

# Inherit from codenvy so we don't have to setup java,
# maven & other eclipse-che dependencies.
FROM codenvy/ubuntu_jre

USER root

RUN curl -sL https://deb.nodesource.com/setup_6.x | bash -

RUN apt-get -y install nodejs && \
    apt-get -y clean && \
    rm -rf /var/lib/apt/lists/*

#USER user

WORKDIR /projects

EXPOSE 3000 5000 9000

CMD tail -f /dev/null


