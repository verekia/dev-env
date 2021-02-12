ARG VARIANT="14-buster"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Global packages
RUN su node -c "npm i -g ts-node"

COPY aliases.sh /home/node/
RUN cat /home/node/aliases.sh >> /home/node/.bashrc
