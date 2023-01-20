#FROM node:14
#ENV NODE_ENV=development
#WORKDIR /var/www
#ARG PORT_BUILD=3000
#ENV PORT=$PORT_BUILD
#EXPOSE $PORT_BUILD
#COPY . .
#RUN npm install 
#ENTRYPOINT ["npm", "start"]
FROM node:latest
ENV NODE_ENV=development
COPY . /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT ["npm", "start"]
EXPOSE 3000
