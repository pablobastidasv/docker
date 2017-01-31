FROM node:6-alpine
MAINTAINER Pablo Bastidas V. pablobastidasv@gmail.com
RUN npm install -g angular-cli
WORKDIR /usr/src/app
EXPOSE 4200 49153
ENTRYPOINT ["ng","serve"]
CMD ["--host", "0.0.0.0"]
