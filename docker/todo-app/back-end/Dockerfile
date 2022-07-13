FROM node:14-alpine
WORKDIR /back-end
EXPOSE 3001
COPY . .
RUN npm install
CMD ["npm" , "start"] 

# nota: Na build da imagem -> Só usar o . quando o dockerfile estiver no mesmo arquivo. Se estiver em qualquer outro precisa dar o caminho durante o build da imagem (nesse caso: ./todo-app/back-end/)