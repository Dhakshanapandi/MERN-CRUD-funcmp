FROM node:17 

WORKDIR /client 

COPY package.json /client 

RUN npm install 

COPY . /client 

EXPOSE 3000

CMD ["npm","run","start"]

