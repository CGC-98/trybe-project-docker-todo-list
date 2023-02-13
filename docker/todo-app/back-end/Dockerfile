FROM node:14
WORKDIR /docker
EXPOSE 3001

ADD ./node_modules.tar.gz .

COPY ./src/ .
COPY ./.gitignore .
COPY ./package-lock.json .
COPY ./package.json .

CMD ["npm", "start"]