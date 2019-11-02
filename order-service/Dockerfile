FROM node:latest
LABEL maintainer="Hjörtur J, Ívar K, Guðrún M"

ENV NODE_ENV production
ENV PORT=80

COPY . /app
WORKDIR /app
RUN npm install

ENTRYPOINT ["npm", "run", "start"]
