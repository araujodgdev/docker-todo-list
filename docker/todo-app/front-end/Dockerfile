FROM node:16-alpine

WORKDIR /app/front-end

EXPOSE 3000

ADD node_modules.tar.gz /app/front-end/

COPY ./ /app/front-end/

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
