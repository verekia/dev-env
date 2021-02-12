ARG VARIANT="14-buster"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Global packages
RUN su node -c "npm i -g ts-node"

RUN echo "alias gs='git status'" >> /home/node/.bashrc
