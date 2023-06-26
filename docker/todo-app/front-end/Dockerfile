
# Build da imagem 'todobackend'
FROM node:16-alpine

# Expor a porta 3001
EXPOSE 3000

# Definir o diretório de trabalho
WORKDIR /app/front-end

# Adicionar o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# Copiar todos os arquivos da pasta back-end para a imagem
COPY . .

# Ponto de entrada padrão
ENTRYPOINT [ "npm" ]

# Comando para iniciar a aplicação
CMD ["start"]
