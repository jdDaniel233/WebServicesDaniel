from node:20.10.0-alpine3.18

WORKDIR package.json .

RUN npm i

COPY index.js .

EXPOSE 3000

CMD [ "node", "index.js"]