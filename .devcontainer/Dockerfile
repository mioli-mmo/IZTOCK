# Imagem base com Node.js (usa Debian)
FROM mcr.microsoft.com/devcontainers/javascript-node:22

# Instalar Angular CLI globalmente
RUN npm install -g @angular/cli

# Instalar utilitários opcionais
RUN apt-get update && apt-get install -y git curl

# Configuração de ambiente
WORKDIR /workspace