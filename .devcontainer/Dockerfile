FROM mcr.microsoft.com/devcontainers/typescript-node:22

# Go 1.26
RUN wget https://go.dev/dl/go1.26.1.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go1.26.1.linux-amd64.tar.gz && \
    rm go1.26.1.linux-amd64.tar.gz && \
    echo 'export PATH=$PATH:/usr/local/go/bin' >> /etc/bash.bashrc

# pnpm install
RUN npm install -g pnpm

WORKDIR /workspace
