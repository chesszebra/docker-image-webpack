FROM chesszebra/node:8.5

# Run as root
USER root

# Install webpack
RUN npm install --global webpack

# Run as node
USER node

ENTRYPOINT ["webpack"]
