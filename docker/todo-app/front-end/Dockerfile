# Use a imagem base do Node.js na versão 16 no Alpine
FROM node:16-alpine

# Exponha a porta 3000
EXPOSE 3000

# Defina o diretório de trabalho
WORKDIR /app/front-end

# Adicione o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# Copie todos os arquivos da pasta front-end para a imagem
COPY . .

ENTRYPOINT [ "npm" ]
# Defina o comando padrão para iniciar a aplicação
CMD ["start"]