FROM node:latest
COPY . /hello-reactapp
RUN cd /hello-reactapp; npm install
EXPOSE 3000
WORKDIR /hello-reactapp 
ENTRYPOINT ["npm", "start"]