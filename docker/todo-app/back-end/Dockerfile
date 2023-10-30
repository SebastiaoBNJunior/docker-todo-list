
# Use a imagem base do Node.js na versão 16 no Alpine
FROM node:16-alpine

# Exponha a porta 3001
EXPOSE 3001

# Defina o diretório de trabalho
WORKDIR /app/back-end

# Adicione o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz /app/back-end

# Copie todos os arquivos da pasta back-end para a imagem
COPY . /app/back-end

# Defina o comando padrão para iniciar a aplicação
CMD ["npm", "start"]
