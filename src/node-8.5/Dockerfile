FROM registry.gitlab.com/chesszebra/docker/node:8.1-cli

# Run as root
USER root

# Install webpack
RUN npm install --global webpack

# Run as node
USER node

ENTRYPOINT ["webpack"]
