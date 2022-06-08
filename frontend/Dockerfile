ARG NODE_VERSION

FROM node:${NODE_VERSION}-buster

ARG APP_NAME
RUN usermod -aG root node

WORKDIR /app/${APP_NAME}


EXPOSE 3000
CMD npm run start