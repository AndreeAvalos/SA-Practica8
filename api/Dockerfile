FROM node:alpine
WORKDIR /server
COPY package.json . 
COPY package-lock.json .
RUN npm i express \
    && npm i body-parser \
    && npm i mysql
COPY index.js . 
CMD ["npm", "start"]