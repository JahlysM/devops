FROM node:alpine

WORKDIR /app

# docker build -t exam-devops-1 .
# docker images
# docker run -it 947984daf4f9 sh


# quand on modifie localement ca modifie la page

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
