FROM debian:11.2

#WORKDIR /app
#COPY . .
#RUN yarn install --production

#CMD ["node", "/app/src/index.js"]
RUN apt-get update
RUN apt-get install iputils-ping -y
RUN apt-get install curl -y
RUN apt-get install procps -y
CMD ["sh"]