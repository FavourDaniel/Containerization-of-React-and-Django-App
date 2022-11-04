FROM node:13-alpine AS builder

RUN mkdir /backend
WORKDIR /frontend
RUN npm install
COPY package.json ./
COPY . .
RUN npm run build



FROM nginx:alpine

WORKDIR /usr/share/nginx/html
RUN rm -rf ./*
COPY --from=build /frontend/build .
EXPOSE 3000 80
CMD ["nginx", "-g", "daemon off;"]