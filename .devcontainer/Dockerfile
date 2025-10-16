FROM mcr.microsoft.com/devcontainers/javascript-node:20

WORKDIR /workspace

# Instala o Yarn
RUN corepack enable && corepack prepare yarn@stable --activate

# Copia o código do projeto
COPY . .