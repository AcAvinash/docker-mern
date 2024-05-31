FROM node:alpine

WORKDIR /app

COPY ./package.json ./

RUN npm i

COPY . ./

ENV MONGO_DB_CLOUD_URL=mongodb+srv://AvinashKumarSingh:Avinash@doc-contact-manager.io3ysrz.mongodb.net/?retryWrites=true&w=majority&appName=doc-contact-manager
ENV MONGO_DB_DATABASE=doc-contact-manager
ENV JWT_SECRET_KEY=$2a$10$wTOxgJsVB8xStAQO1saV
ENV NODE_ENV=production

ENV PORT=4000


CMD ["npm","start"]
