FROM node:14-alpine

WORKDIR /app

COPY node_modules.tar.gz .
COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
