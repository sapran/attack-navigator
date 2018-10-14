# Build stage

FROM node:latest 

WORKDIR /nav-app/

# copy over needed files
COPY . ./

# install packages and build 
RUN npm install && npm rebuild node-sass --force

EXPOSE 9200

CMD npm start
