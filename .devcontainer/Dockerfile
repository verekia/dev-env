ARG VARIANT="14-buster"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Global packages
RUN su node -c "npm i -g ts-node"

RUN echo "\n\
alias gs='git status'\n\
alias ga='git add'\n\
alias gc='git commit'\n\
alias gch='git checkout'\n\
alias gpull='git pull'\n\
alias gpush='git push'\n\
alias gpushno='git push --no-verify'\n\
alias gs='git status'\n\
alias gd='git diff'\n\
alias ns='npm start'\n\
alias nt='npm test'\n\
alias nl='npm run lint'\n\
alias nr='npm run'\n\
alias ni='npm install'\n\
alias y='yarn'\n\
alias ys='yarn start'\n\
alias yt='yarn test'\n\
alias yl='yarn lint'\n\
" >> /home/node/.bashrc
