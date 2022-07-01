FROM debian

#WORKDIR /app
#COPY . .
#RUN yarn install --production

#CMD ["node", "/app/src/index.js"]
RUN apt-get update
RUN apt-get install iputils-ping -y
RUN apt-get install curl -y
RUN apt-get install procps -y
RUN apt-get install vim-tiny -y
#CMD sh -c 'trap "exit" TERM; while true; do sleep 1; done'