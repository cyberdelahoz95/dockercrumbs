FROM node:12.19.0
COPY ["package.json", "package-lock.json", "/usr/src/"]
WORKDIR /usr/src
ENV PATH /usr/src/node_modules/.bin:$PATH
RUN npm install --silent
COPY [".","/usr/src"]
EXPOSE 3000